# Python decorators
```python
def decorate(fn):
	def return_fn(inputs):
		return do_something to input
	return return_fn


def a_function(inputs):
	return output

@decorate
def a_function(inputs):
	return output

```