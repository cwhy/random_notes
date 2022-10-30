```python
my_list = [1, 2, 3]
for a in my_list:
	print(a)
# 1
# 2
# 3

new_list = []
for a in my_list:
	new_list.append(sqrt(a))
	# new_list: [sqrt(a)]

# map(sqrt, my_list)

for i in range(10):
	print(i)
# 1
# 2
# ...

```

Not allowed
```python
my_list = [1, 2, 3]
for a in my_list:
	my_list.append(a)
	#[1, 2, 3, 1]
```

```js
let center = [1, 2, 3]
center.map(x=>x+1)
//[2, 3, 4]
```

```python
center = [1, 2, 3]
new_array = []
for c in center:
	new_array.append(c + 1)
print(new_array)
# [2, 3, 4]
```

## `for` comprehension
```python
center = [1, 2, 3]
[c+1 for c in center]
# [2, 3, 4]
```

```python
def process(c):
	return c + 1

[process(c) for c in center]
# [2, 3, 4]
```

- with conditions (like `filter` in `js`)
```python
# get even numbers
[x for x in range(30) if (x % 2) == 0]
```

## Enumerate
```python
[x for x in enumerate(["adsf", "asdf", "df4e"])]
# [(0, 'adsf'), (1, 'asdf'), (2, 'df4e')]
```

