# Collections
### Tuples
```python
a = (1, 2)
x, y = a
x, y  # 1, 2

a[0]  # 1
a[1]  # 2

a + a  # (1, 2, 1, 2)
a * 3  # (1, 2, 1, 2, 1, 2)

b = (1, 2, 3, 4, 5, 6, 7)
b - a
# TypeError: unsupported operand type(s) for -: 'tuple' and 'tuple'
```
### Lists
```python
a = [1, 2]
x, y = a
x, y # 1, 2

a[0]  # 1
a[1]  # 2

a + a  # [1, 2, 1, 2]
a * 3  # [1, 2, 1, 2, 1, 2]

a.append(3)
a  # [1, 2, 3]
a.append(3)
a  # [1, 2, 3, 3]
```
### Sets
```python

```