## Operators
### `#` comments
```python
# This will not run
2  # things after # will not run
```
- put space before and after the `#` as a convention

### `=` assignments
```python
1  # 1
a = 1
a  # 1
```


### `==/is` equality
```python
2 == 2  # True
2 is True  # False
(2 == 2) is True  # True
```
- use `is` when right side is `Boolean` or `None`

## functions (Callable)
### `type()` get type of expression
```python
type(None)  # NoneType
type(True)  # bool
type(2)     # int
type(2.0)   # float
type("hello world") # str
type(int)   # type
```

### `print()` Print stuff to console
```python
print("hi")
# in console:
# > hi
```