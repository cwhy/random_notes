# TidyPolars Intro
## 5 basic operations
- `select()`
- `filter()`
- `summarise()`
- `arrange()`
- `mutate()`

```python
import tidypolars as tp
from tidypolars import col, desc

df = tp.Tibble(x = range(3), y = range(3, 6), z = ['a', 'a', 'b'])
(
    df
    .select('x', 'y', 'z')
    .filter(col('x') < 4, col('y') > 1)
    .arrange(desc('z'), 'x')
    .mutate(double_x = col('x') * 2,
            x_plus_y = col('x') + col('y'))
)
```