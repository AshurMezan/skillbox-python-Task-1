# 2.6 Итоги пройденных тем. Проверьте себя

Задача из SkillBox

Цель практической работы
Научиться:  работать с переменными; присваивать значения, выводить значение переменной через print; работать с функцией input.

Что входит в работу
Найти пропавшую переменную.
Исправить программу с названиями цвета.
Вывести на экран фразу о животных.
Исправить программу о доступе к системе.
Написать запрос о городах вылета и прилёта.
Задача повышенной сложности. Поменять местами значения двух переменных.
Для выполнения практической работы используйте подготовленный нами шаблон.

## Задача 1. Пропавшая переменная
Что нужно сделать

Найдите в программе необъявленную переменную и объявите её, присвоив ей значение ‘Кот’.

client = ‘Петя’
print(client)
print(‘ и ’)
print(pet)

Что оценивается

Результат вывода корректен, нет ошибок. Присвоено значение переменной pet.
Отсутствуют пробелы после print и перед скобками: print () — неверно, print() — верно.
Нет пробелов и внутри скобок.
Знак равенства выделен пробелами с двух сторон: client = ‘Петя’ — верно, client=‘Петя’ — неверно.

## Задача 2. Цвета
Что нужно сделать

Исправьте программу так, чтобы в результате её выполнения на экран в одну строку выводился текст: Red Blue Green RedGreenBlue Blue GreenBlue.

r = 'Red'
g = 'Green'
b = 'Blue'

print(b, r, g, b, g + b, b + b + g, b)

## Задача 3. Животные
Что нужно сделать

Создайте две переменные с именами «Первое животное» и «Второе животное» на английском языке. Запишите в первую переменную слово «Заяц», а во вторую — «Черепаха». Используя эти переменные, выведите на экран текст «Заяц спит, Черепаха идёт» в одну строку.

## Задача 4. Вход в систему
Что нужно сделать

Исправьте программу и допишите необходимые команды для получения нужного результата. Будьте внимательны при исправлении и помните о правилах названия переменных.

Программа:

first name = input('Введите имя пользователя: ')
grииting = 'Утро доброе'
print(greeting, first name)
intro = "К сожалению, у Вас нет доступа к системе."
info == "Пожалуйста, обратитесь к системному администратору."

## Задача 5. Полёт
Что нужно сделать

Напишите программу для сервиса заказа билетов, которая запрашивает у пользователя город вылета и город прилёта. Затем выведите их в одну строку через тире. Обратите внимание на свои переменные: названия должны отражать содержимое.

##  Задача 6. Повышенная сложность. Обмен значений двух переменных
Что нужно сделать

Дана программа, которая запрашивает у пользователя два слова, а затем выводит их на экран два раза. Скопируйте эту программу в редактор и проверьте.

a = input('Введите первое слово: ')
b = input('Введите второе слово: ')
print(a, b)
(стереть эту строчку и вставить свой код здесь)
print(a, b)

Задача: поменять значения переменных a и b местами. Изменять, удалять, менять местами первую, вторую, третью и последнюю строчки нельзя. Но в четвёртую строку можно вставлять сколько угодно кода, не трогая последний принт. 
