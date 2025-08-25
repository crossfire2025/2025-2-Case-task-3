def main():
    print("Введите N целых чисел (через пробел или запятую):")
    input_str = input("> ").replace(',', ' ')

    try:
        # Преобразуем введенную строку в список целых чисел
        array = list(map(int, input_str.split()))

        # Находим все отрицательные числа
        negative_elements = [x for x in array if x < 0]
        total = sum(negative_elements)

        # Выводим результат в консоль
        if negative_elements:
            print(f"\nСумма отрицательных элементов: {total}")
            print("Элементы, попавшие в сумму:", ', '.join(map(str, negative_elements)))
        else:
            print("\nОтрицательных элементов нет.")
    except ValueError:
        print("\nОшибка: введите только целые числа, разделённые пробелами или запятыми.")

if __name__ == "__main__":
    main()
