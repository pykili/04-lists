## Домашнее задание

Вам нужно написать программу, которая будет рисовать.

Программа должна спрашивать имя длинной не менее 4 символов.

Домашнее задание поделено на 2 части.

#### Первая часть

В первой части предлагается заполнить матрицу размером `NxN`, где `N` - это длина введенного имени.
Заполнить матрицу нужно определенным образом в зависимости от варианта, ниже приведены примеры для имени «иван»

**Варианты 1, 7**

Справа-налево

```
н а в и
н а в и
н а в и
н а в и
```


**Варианты 2, 4, 6**

Сверху-вниз

```
и и и и
в в в в
а а а а
н н н н
```

**Варианты 3, 5**

снизу-вверх

```
н н н н
а а а а
в в в в
и и и и
```


#### Вторая часть

Следует расплющить матрицу в одномерный список, соединив её строки одну за другой. Например, для варианта 3 должен получится следующий список:

```python
['н', 'н', 'н', 'н', 'а', 'а', 'а', 'а', 'в', 'в', 'в', 'в', 'и', 'и', 'и', 'и']
```

> Программа должна выдавать правильное решение для имени длиной **минимум 4 символа**

И вывести на экран список элементов в соответствии с номером варианта (нумерация с нуля):

- `1 вариант`:  все элементы, начиная с 1 и до конца с шагом 3
- `2 вариант`: с 12 по 3 элементы в обратном порядке
- `3 вариант`: с начала и до 11 элемента
- `4 вариант`: все элементы в обратном порядке
- `5 вариант`: с 11 элемента и до конца
- `6 вариант`: с 2 по 15 элементы, индексы которых в этом списке четные
- `7 вариант`: с 2 по 15 элементы, индексы которых в этом списке нечетные
