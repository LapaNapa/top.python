import random

# Генерируем случайное число от 1 до 10
random_number = random.randint(1, 10)

# Запрашиваем у пользователя ввод числа
guess = int(input("Угадайте число от 1 до 10: "))

# Сравниваем введенное пользователем число с сгенерированным случайным числом
if guess == random_number:
    print("Поздравляем! Вы угадали число!")
else:
    print("Увы, вы не угадали. Загаданное число было:", random_number)
