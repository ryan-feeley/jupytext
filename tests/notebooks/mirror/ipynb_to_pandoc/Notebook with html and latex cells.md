---
jupyter:
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
  nbformat: 4
  nbformat_minor: 2
---

::: {.cell .code}
``` {.python}
%%html
<p><a href="https://github.com/mwouts/jupytext", style="color: rgb(0,0,255)">Jupytext</a> on GitHub</p>
```
:::

::: {.cell .code}
``` {.python}
%%latex
$\frac{\pi}{2}$
```
:::

::: {.cell .code}
``` {.python}
%load_ext rpy2.ipython
```
:::

::: {.cell .code}
``` {.python}
%%R
library(ggplot2)
ggplot(data=data.frame(x=c('A', 'B'), y=c(5, 2)), aes(x,weight=y)) + geom_bar()
```
:::

::: {.cell .code}
``` {.python}
%matplotlib inline
import pandas as pd
pd.Series({'A':5, 'B':2}).plot(figsize=(3,2), kind='bar')
```
:::
