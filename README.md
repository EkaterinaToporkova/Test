Тестовое задание на позицию Junior programmer (Python)

**Задание 1.** На языке Python написать алгоритм (функцию) определения четности целого числа, который будет аналогичен нижеприведенному по функциональности, но отличен по своей сути.

Исходный код:
def isEven(value):
    return value % 2 == 0
    
Мой код:
def isEven2(value):
    return value & 1 == 0

Сравним два варианта.

В первую очередь буду сравнивать время выполнения (использую IDE Atom).
Для первого кода время выполнения: 0.080 s
Для второго кода время выполнения: 0.088 s

Время выполнения отличается на доли секунд, но можно сделать вывод, что первый код выполняется быстрее. Значит минус второй реализации во времени выполнения, по сравнению с первой.

Теперь узнаем, сколько памяти занимает каждая из функция. Для этого использую модуль sys.
Результат для первого кода: 144 байта
Результат для второго кода: 144 байта

Можно сделать вывод, что по занимаемой памяти два кода равны.

Таким образом, первый код более оптимальный для использования, но не значительно.

**Задание 2** На языках Python(2.7) написать минимум по 2 класса реализовывающих циклический буфер.

Реализация через индексы: [Код тут](https://github.com/EkaterinaToporkova/Test/blob/main/%D0%A0%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F%20%D1%87%D0%B5%D1%80%D0%B5%D0%B7%20%D0%B8%D0%BD%D0%B4%D0%B5%D0%BA%D1%81%D1%8B)

Реализция с помощью связных списков: [Код тут](https://github.com/EkaterinaToporkova/Test/blob/main/%D0%A0%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F%20%D1%81%20%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E%20%D1%81%D0%B2%D1%8F%D0%B7%D0%BD%D1%8B%D1%85%20%D1%81%D0%BF%D0%B8%D1%81%D0%BA%D0%BE%D0%B2:)








