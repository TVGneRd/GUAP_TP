# GUAP Лабораторная работа №2

Задание:

● Необходимо разделение на h и cpp файлы для каждого класса. Функция main должна располагаться в отдельном cpp файле.
● Элемент очереди/стека/списка необходимо реализовать с помощью класса или
структуры.
● Необходимо работать с динамическим выделением памяти. Не использовать STL
библиотеку.
● Необходимо написать для каждого класса: необходимое число конструкторов (без
параметров, с параметрами, копирования) и деструктор.
● Необходимо реализовать передачу и возвращение объектов класса по значению, по
указателю и по ссылке.
● Реализовать пользовательское меню согласно заданию. Пользователю должны быть
доступны все действия по работе с объектом класса.
● Необходимо использовать аргументы по умолчанию и спецификатор explicit.
● Внимательно читайте задание. Перегрузка операторов возможна как для работы со
встроенными типами данных (числами), так и с экземплярами вашего класса.
● У пользователя должна быть возможность ввода, модификации и удаления значений
(обнуление) среди прочих доступных действий. Весь перечень действий необходимо определить
студенту самостоятельно исходя из задания и создаваемых классов. Например, при работе с
очередью необходимо иметь возможности очищения, добавления, удаления и пр.
● В main вид унарной операции должен иметь вид: a = b++; a = ++b; a = --b; a = b--. На
экран необходимо выводить a и b. Принцип действия постфиксных и префиксных операторов
должен быть сохранен.
● В main вид бинарной операции должен иметь вид: a = b + c. На экран необходимо
вывести a, b и с для проверки результата вычисления.
● Номер варианта соответствует номеру студента в списке. Каждому студенту
необходимо выполнить оба задания.


Вариант задания:

• Задание 1. Унарная операция
Создать класс “Целое число”. Необходимо перегрузить следующие операторы: оператор префиксного декрементирования как метод для вычитания пользовательского числа; оператор постфиксного декрементирования как метод для вычитания единицы; оператор префиксного инкрементирования как дружественную функцию для прибавления пользовательского числа; оператор постфиксного инкрементирования как дружественную функцию для прибавления единицы; оператор ! как метод для возвращения отрицательного значения, хранящегося в экземпляре класса.

• Задание 2. Бинарная операция
Создать класс "Стек". Размер и значения стека задаются пользователем с клавиатуры. Необходимо перегрузить следующие операторы для работы с числами: +, +=, -, -=, *, *=, /, /=. Необходимо учитывать то, что пользовательское число и объект класса могут находится и слева и справа от оператора. На усмотрение студента остается решение какой оператор какой перегрузки требует (метод или дружественная функция).

Управление:
Клавиши «ВВЕРХ», «ВНИЗ» - передвижение по пунктам меню. 
Клавиша «ENTER - выбор пункта меню.

![image](https://user-images.githubusercontent.com/43295090/167473647-ea4bfe15-ab2f-411d-ae41-5f4c49c43d10.png)
![image](https://user-images.githubusercontent.com/43295090/167473708-6895221b-228b-4093-9d0b-c40192722be5.png)
![image](https://user-images.githubusercontent.com/43295090/167473727-80cc9fd1-8d78-4931-a400-d857f8858e59.png)
![image](https://user-images.githubusercontent.com/43295090/167473751-45d6565d-fb85-4339-b1d4-d1b95a933d3b.png)

