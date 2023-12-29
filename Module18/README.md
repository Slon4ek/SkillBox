## Цели практической работы
- Уметь применять различные способы форматирования строк для чистоты кода и для вывода значений на экран.
- Отработать представление информации в Python в виде строки:
  - уметь разбивать вводимый текст по разделителю и составлять из него список слов;
  - уметь «склеивать» слова списка более оптимизированным методом, без конкатенации;
  - уметь использовать другие методы строк для обработки текста, в том числе методы проверки текста и методы работы с регистром.
## Что входит в работу
- Задача 1. Меню ресторана.
- Задача 2. Самое длинное слово.
- Задача 3. Файлы.
- Задача 4. Заглавные буквы.
- Задача 5. Пароль.
- Задача 6. Сжатие.
- Задача 7. IP-адрес 2.
- Задача 8. Бегущая строка.
- Задача 9. Анализ комментариев

Во всех задачах для склеивания строк используйте метод join, а не конкатенацию.

## Задача 1. Меню ресторана
### Что нужно сделать
Один ресторан заказал вам написать приложение, которое в один клик отображало бы пользователю доступное меню в удобном виде. Для этого ресторан любезно предоставил свой сайт, откуда можно получить актуальную информацию о меню в виде идущих подряд названий.

Напишите программу, которая выводит это меню на экран. На вход подаётся строка из названий блюд, разделённых символом «;», а на выходе эти названия перечисляются через запятую и пробел.

Пример:

```
Доступное меню: утиное филе;фланк-стейк;банановый пирог;плов

На данный момент в меню есть: утиное филе, фланк-стейк, банановый пирог, плов
```
### Что оценивается
- Результат вычислений корректен.
- input содержит корректные приглашения для ввода. 
- Формат вывода соответствует примеру.
- Переменные и функции имеют значащие имена, не только a, b, c, d (подробнее об этом в видео 2.3).

## Задача 2. Самое длинное слово
### Что нужно сделать
Пользователь вводит строку, содержащую пробелы. Найдите в ней самое длинное слово, выведите это слово и его длину. Если таких слов несколько, выведите первое из них.

Пример 1:

```
Введите строку: я есть строка
Самое длинное слово: строка
Длина этого слова: 6
```

Пример 2:

```
Введите строку: а б
Самое длинное слово: а
Длина этого слова: 1
```

Пример 3:

```
Введите строку:    б
Самое длинное слово: б
Длина этого слова: 1
```
### Что оценивается
- Результат вычислений корректен.
- input содержит корректные приглашения для ввода. 
- Формат вывода соответствует указанному в задаче.
- Переменные и функции имеют значащие имена, не только a, b, c, d (подробнее об этом в видео 2.3).

## Задача 3. Файлы
### Что нужно сделать
В одной IT-компании существует негласный закон об именовании текстовых документов:

1. Название файла не должно начинаться на один из специальных символов: `@№$%^&\*()`.
1. Файл заканчивается расширением `.txt` или `.docx`.

Напишите программу, которая получает на вход полное название файла и проверяет его по этим правилам.

Пример 1:

```
Название файла: @example.txt

Ошибка: название начинается на один из специальных символов.
```

Пример 2:

```
Название файла: example.ttx

Ошибка: неверное расширение файла. Ожидалось .txt или .docx.
```

Пример 3:

```
Название файла: example.txt

Файл назван верно.
```
### Что оценивается
- Результат вычислений корректен.
- input содержит корректные приглашения для ввода. 
- Формат вывода соответствует примеру.
- Переменные и функции имеют значащие имена, не только a, b, c, d (подробнее об этом в видео 2.3).

## Задача 4. Заглавные буквы
### Что нужно сделать
Пользователь вводит строку. Напишите программу, которая изменяет регистр символов в этой строке так, чтобы первая буква каждого слова была заглавной, а остальные буквы — строчными.

Пример:

```
Введите строку: Кажется, я забыл выключить утюг.

Результат: Кажется, Я Забыл Выключить Утюг.
```
### Что оценивается
- Результат вычислений корректен.
- input содержит корректные приглашения для ввода. 
- Формат вывода соответствует указанному в задаче.
- Переменные и функции имеют значащие имена, не только a, b, c, d (подробнее об этом в видео 2.3).

## Задача 5. Пароль
### Что нужно сделать
При регистрации на сайте помимо логина нужно ещё придумать надёжный пароль. Этот пароль должен состоять минимум из восьми символов, в нём должны быть хотя бы одна большая буква и хотя бы три цифры. Тогда он будет считаться надёжным. 

Напишите программу, которая запрашивает у пользователя пароль до тех пор, пока он не введёт надёжный пароль. Используется латиница.

Пример:

```
Придумайте пароль: qwerty
Пароль ненадёжный. Попробуйте ещё раз.
Придумайте пароль: qwerty12
Пароль ненадёжный. Попробуйте ещё раз.
Придумайте пароль: qwerty123
Пароль ненадёжный. Попробуйте ещё раз.
Придумайте пароль: qWErty123
Это надёжный пароль!
```
### Что оценивается
- Результат вычислений корректен.
- input содержит корректные приглашения для ввода. 
- Формат вывода соответствует примеру.
- Переменные и функции имеют значащие имена, не только a, b, c, d (подробнее об этом в видео 2.3).

## Задача 6. Сжатие
### Что нужно сделать
С увеличением объёма данных возникла потребность в сжатии этих данных без потери важной информации. Для этого было придумано кодирование, которое осуществляется следующим образом:

`s = 'aaaabbсaa'` преобразуется в `'a4b2с1a2'`, то есть группы одинаковых символов исходной строки заменяются на этот символ и количество его повторений в этой позиции строки.

Напишите программу, которая считывает строку, кодирует её предложенным алгоритмом и выводит закодированную последовательность на экран. Кодирование должно учитывать регистр символов.

Пример:

```
Введите строку: aaAAbbсaaaA

Закодированная строка: a2A2b2с1a3A1
```
### Что оценивается
- Результат вычислений корректен.
- input содержит корректные приглашения для ввода. 
- Формат вывода соответствует примеру.
- Переменные и функции имеют значащие имена, не только a, b, c, d (подробнее об этом в видео 2.3).

## Задача 7. IP-адрес 2
### Что нужно сделать
При написании клиент-серверного приложения часто приходится работать с теми самыми IP-адресами. Как вы уже знаете, IP-адрес состоит из четырёх целых чисел в диапазоне от 0 до 255, разделённых точками.

Пользователь вводит строку. Напишите программу, которая определяет, является ли заданная строка правильным IP-адресом. Обеспечьте контроль ввода, где предусматривается ввод целых чисел от 0 до 255, а также точки между ними.

Пример 1:

```
Введите IP: 128.16.35.a4
a4 — это не целое число.
```

Пример 2:

```
Введите IP: 240.127.56.340
340 превышает 255.
```

Пример 3:

```
Введите IP: 34.56.42,5
Адрес — это четыре числа, разделённые точками.
```

Пример 4:

```
Введите IP: 128.0.0.255
IP-адрес корректен.
```
### Что оценивается
- Результат вычислений корректен.
- input содержит корректные приглашения для ввода. 
- Формат вывода соответствует примеру.
- Переменные и функции имеют значащие имена, не только a, b, c, d (подробнее об этом в видео 2.3).

## Задача 8. Бегущая строка
### Что нужно сделать
В одной из практических работ вы писали для табло программу, которая циклически сдвигает элементы списка чисел вправо на K позиций. В этот раз вы работаете с двумя строками. Нужно проверить, не равна ли на самом деле одна другой. Возможно, одна из них просто немного сдвинута.

Пользователь вводит две строки. Напишите программу, которая определяет, можно ли первую строку получить из второй циклическим сдвигом.

Опционально: если получить можно, то выведите значение этого сдвига.

Пример 1:

```
Первая строка: abcd
Вторая строка: cdab

Первая строка получается из второй со сдвигом 2.
```

Пример 2:

```
Первая строка: abcd
Вторая строка: cdba

Первую строку нельзя получить из второй с помощью циклического сдвига.
```
### Что оценивается
- Результат вычислений корректен.
- input содержит корректные приглашения для ввода. 
- Формат вывода соответствует примеру.
- Переменные и функции имеют значащие имена, не только a, b, c, d (подробнее об этом в видео 2.3).


## Задача 9. Анализ комментариев

### Контекст 
Вы разрабатываете программу, которая анализирует тексты, написанные пользователем, и выдаёт статистику по использованию заглавных и строчных букв. 
Это может быть полезно, например, при анализе комментариев в социальных сетях или обработке текстовых данных для исследований.

### Задача 
Напишите программу, которая считывает строку и выводит количество заглавных и строчных букв в строке, используя методы строк. 
Программа должна это делать за один проход по строке.
Решение должно быть оформлено в виде функции, которая принимает на вход строку-текст, а на выход возвращает два числа (количество заглавных и строчных букв).
```
# Пример:
text = input("Введите строку для анализа: ")
uppercase, lowercase = count_uppercase_lowercase(text)
print("Количество заглавных букв:", uppercase)
print("Количество строчных букв:", lowercase)


# Вывод в консоли:

Введите строку для анализа: Hello World!
Количество заглавных букв: 2
Количество строчных букв: 8
```

### Советы
- Вспомните методы строк, которые изучили. Выберите из них те, которые помогут вам выполнить проверку буквы (является ли она заглавной 
или нет).
- Чтобы вернуть несколько элементов из функции, перечислите их через запятую:
	- return a, b


## Что оценивается в практической работе
- Практическая работа сдана через GitLab.
- Структура папок и файлов репозитория соответствует репозиторию python_basic.
- Все задачи выполнены в соответствующих папках и файлах `main.py`.
- Описания коммитов осмысленны и понятны: `111`, `done`, `«я сделалъ»` — неверно; `added m15 homework`, `14.3 fix: variables naming` — верно.
- Использованы именованные индексы, не просто `i` (подробнее в видео 7.2).
- Использованы правильные числа, без дополнительных действий со стороны пользователя, без `+1` (подробнее об этом в видео 7.4).
- Правильно оформлен `input`, без пустого приветствия для ввода (подробнее об этом в видео 2.3).
- Переменные и функции имеют значащие имена, не только `a`, `b`, `c`, `d` (подробнее об этом в видео 2.3).
- Есть пробелы после запятых и при бинарных операциях.
- Нет пробелов после имён функций и перед скобками: `print ()`, `input ()` — неверно; `print()` — верно.
- Правильно оформлены блоки `if-elif-else`, циклы и функции; отступы одинаковы во всех блоках одного уровня.
- Для склеивания строк используется метод `join`, а не конкатенация.
## Советы и рекомендации
- [Шпаргалка по методам строк](https://docs.google.com/document/d/1VaZkvdZPYj4L-R7lGUh86otV3oKqS5quU5zWenNPk3w/edit).
- Арифметические операции [PEP8](https://docs.python.org/3.7/reference/expressions.html#operator-precedence) остаются в приоритете. Необходимо вводить and, or.
- Руководство по стилю Python [PEP8](https://www.python.org/dev/peps/pep-0008/) на английском языке.
- Руководство по стилю Python [PEP8](https://pep8.ru/doc/pep8/) на русском языке.
- [Список встроенных функций](https://docs.python.org/3.7/library/functions.html).
## Как отправить работу на проверку
Чтобы выполнить практическую работу, обновите репозиторий python_basic на своём компьютере при помощи IDE PyCharm. Задачи находятся в папке Module18.

Сдайте практическую работу этого модуля через систему контроля версий Git сервиса Skillbox GitLab. В занятии с практической работой напишите «Сделано» и прикрепите ссылку на репозиторий. Ссылки на реплит оставлять не нужно.