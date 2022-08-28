```python
X[2, 4]
X[2, :]
X[:, 4]
X[:100, :]
X[:, :] == X

```

Shuffle along axis
```python
def shuffle_along_axis(a, axis):
    idx = np.random.rand(*a.shape).argsort(axis=axis)
    return np.take_along_axis(a,idx,axis=axis)
```