# Pandas basics
- Concepts
	- csv
	- pandas
	* Dataframe
- Read data
```python
import pandas as pd

train_data = pd.read_csv("/kaggle/input/titanic/train.csv")
```
- View data
```python
train_data.describe()
train_data.head()
train_data.tail()
```

- columns
```python
# recommended
gender_submission['Survived']
gender_submission['Survived'] = 0

gender_submission.Survived
```

- save csv
```python
gender_submission.to_csv("submission.csv")
gender_submission.to_csv("submission.csv", index=False)
```

- Plotting
```python
train_data.plot()
train_data.boxplot(by="Survived", column="Age", figsize=(20, 20))
```

- Query
```python
train_data.query("Survived == 1").query("Pclass == 2")
```

- shape
```python
train_data.shape
```

