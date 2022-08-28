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