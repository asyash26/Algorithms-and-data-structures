## Сравнения подстрок

Дана строка. Нужно уметь отвечать на запросы вида: равны ли подстроки [a..b] и [c..d].

#### Входные данные
Сперва строка S (не более 105 строчных латинских букв). Далее число M — количество запросов.

В следующих M строках запросы a,b,c,d. 0 ≤ M ≤ 105, 1 ≤ a ≤ b ≤ |S|, 1 ≤ c ≤ d ≤ |S|

#### Выходные данные
M строк. Выведите Yes, если подстроки совпадают, и No иначе.

## Z-функция

Постройте Z-функцию для заданной строки s.

#### Входные данные
Первая строка входного файла содержит s (1 ≤ |s| ≤ 106). Строка состоит из букв латинского алфавита.

#### Выходные данные
Выведите значения Z-функции строки s для индексов 2, 3, ..., |s|.

## Разделение выражения на лексемы
Задано числовое выражение, заканчивающееся точкой. Необходимо разбить его на лексемы и вывести каждую на новой строке. Гарантируется, что исходное выражение корректно.

В выражении могут встречаться знаки сложения, вычитания, умножения и скобки. Приоритет операций стандартный. Все числа в выражении целые и принадлежат диапазону LongInt.

#### Входные данные
Первая строка содержит заданное выражение. Его длина не превосходит 100 знаков. Гарантируется, что выражение заканчивается точкой.

#### Выходные данные
Выведите все встречающиеся лексемы выражения по порядку и ровно по одной на каждой строке.