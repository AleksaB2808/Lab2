# Lab2
Функция task1


def task1(number1, znak, number2):
    if znak == '>':
        return number1 > number2
    if znak == '<':
        return number1 < number2
    if znak == '>=':
        return number1 >= number2
    if znak == '<=':
        return number1 <= number2
    if znak == '==':
        return number1 == number2
    if znak == '!=':
        return number1 != number2
    else:
        return False
def task1(number1, znak, number2):: Объявление функции с именем task1, которая принимает три аргумента: number1, znak (оператор сравнения в виде строки) и number2.
if znak == '>':: Проверяет, равен ли аргумент znak строке '>'.
return number1 > number2: Если znak равно '>', возвращает результат сравнения number1 > number2.
if znak == '<':: Проверяет, равен ли аргумент znak строке '<'.
return number1 < number2: Если znak равно '<', возвращает результат сравнения number1 < number2.
if znak == '>=':: Проверяет, равен ли аргумент znak строке '>='.
return number1 >= number2: Если znak равно '>=', возвращает результат сравнения number1 >= number2.
if znak == '<=':: Проверяет, равен ли аргумент znak строке '<='.
return number1 <= number2: Если znak равно '<=', возвращает результат сравнения number1 <= number2.
if znak == '==':: Проверяет, равен ли аргумент znak строке '=='.
return number1 == number2: Если znak равно '==', возвращает результат сравнения number1 == number2.
if znak == '!=':: Проверяет, равен ли аргумент znak строке '!='.
return number1 != number2: Если znak равно '!=', возвращает результат сравнения number1 != number2.
else:: Если ни одно из условий не выполнено (т.е. znak не равен ни одному из известных значений), выполняется следующий блок.
return False: Возвращает False, если znak не соответствует ни одному из операторов сравнения.
Пример использования:

print(task1(5, '>', 3))  # Выведет: True
print(task1(5, '<', 3))  # Выведет: False
print(task1(5, '>=', 5))  # Выведет: True
print(task1(5, '<=', 5))  # Выведет: True
print(task1(5, '==', 5))  # Выведет: True
print(task1(5, '!=', 3))  # Выведет: True
print(task1(5, '??', 3))  # Выведет: False
В каждом из этих примеров функция task1 принимает два числа и оператор сравнения, выполняет соответствующее сравнение и возвращает результат. Если оператор не поддерживается, функция возвращает False.
Функция task2

def task2(text, number):
    if len(text) > number:
        return len(text)
    else:
        return number
def task2(text, number):: Объявление функции с именем task2, которая принимает два аргумента: text (строка) и number (число).
if len(text) > number:: Проверяет, больше ли длина строки text чем значение number.
return len(text): Если длина строки text больше, возвращает длину строки.
else:: Если длина строки text не больше, выполняется следующий блок.
return number: Возвращает значение number.
Пример использования:

print(task2("Hello", 3))  # Выведет: 5
print(task2("Hi", 5))  # Выведет: 5
В первом примере длина строки "Hello" (5) больше, чем число 3, поэтому функция возвращает 5. Во втором примере длина строки "Hi" (2) меньше, чем число 5, поэтому функция возвращает 5.
Функция task3

def task3(number1, number2, number3):
    if number1 == number2 == number3:
        return True
    else:
        return False
def task3(number1, number2, number3):: Объявление функции с именем task3, которая принимает три аргумента: number1, number2 и number3.
if number1 == number2 == number3:: Проверяет, равны ли все три числа друг другу.
return True: Если все три числа равны, возвращает True.
else:: Если числа не равны, выполняется следующий блок.
return False: Возвращает False.
Пример использования:

print(task3(3, 3, 3))  # Выведет: True
print(task3(3, 4, 3))  # Выведет: False
В первом примере все три числа равны (3), поэтому функция возвращает True. Во втором примере числа не равны (3, 4, 3), поэтому функция возвращает False.
Полный исправленный код

# task1
def task1(number1, znak, number2):
    if znak == '>':
        return number1 > number2
    if znak == '<':
        return number1 < number2
    if znak == '>=':
        return number1 >= number2
    if znak == '<=':
        return number1 <= number2
    if znak == '==':
        return number1 == number2
    if znak == '!=':
        return number1 != number2
    else:
        return False

# task2
def task2(text, number):
    if len(text) > number:
        return len(text)
    else:
        return number

# task3
def task3(number1, number2, number3):
    if number1 == number2 == number3:
        return True
    else:
        return False

# Примеры использования:
print(task1(5, '>', 3))  # Выведет: True
print(task1(5, '<', 3))  # Выведет: False
print(task1(5, '>=', 5))  # Выведет: True
print(task1(5, '<=', 5))  # Выведет: True
print(task1(5, '==', 5))  # Выведет: True
print(task1(5, '!=', 3))  # Выведет: True
print(task1(5, '??', 3))  # Выведет: False

print(task2("Hello", 3))  # Выведет: 5
print(task2("Hi", 5))  # Выведет: 5

print(task3(3, 3, 3))  # Выведет: True
print(task3(3, 4, 3))  # Выведет: False
