# young_table

**Таблица Юнга** *m x n* представляет собой матрицу размером *m x n*, элементы которой в каждой строке отсортированы слева направо, а в каждом столбце - сверху вниз. Некоторые элементы таблицы Юнга могут быть равны ∞, что трактуется как отсутсвие элемента. Таким образом, таблицу Юнга можно использовать для хранения *r <= mn* конечных чисел.

## young_table@0.0.1
Требуется реализовать таблицу Юнга размером *3 x 3*, поддерживающую следующие операции:
- вставка элемента в таблицу
- вывод таблицы на экран

### Входные данные
- `+ число` - вставить число
- `=` - вывести таблицу на экран
- `q` - выйти


### Примеры
```
∞ ∞ ∞
∞ ∞ ∞
∞ ∞ ∞

+ 1

1 ∞ ∞ 
∞ ∞ ∞ 
∞ ∞ ∞ 

+ 2

1 2 ∞ 
∞ ∞ ∞ 
∞ ∞ ∞ 

+ 4

1 2 ∞ 
4 ∞ ∞ 
∞ ∞ ∞ 

+ 6

1 2 ∞ 
4 6 ∞ 
∞ ∞ ∞ 

+ 7

1 2 ∞ 
4 6 ∞ 
7 ∞ ∞ 

+ 8

1 2 ∞ 
4 6 ∞ 
7 8 ∞ 

+ 5

1 2 ∞ 
4 6 ∞ 
5 7 8 

+ 3

1 2 ∞ 
3 4 6 
5 7 8 

+ 3

1 2 3 
3 4 6 
5 7 8 

q
```
