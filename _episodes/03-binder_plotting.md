---
title: "Using Binder for sharing dynamics notebooks"
teaching: 5
exercises: 5
questions:
- "How can you share notebooks so they are interactive rather than static?"
objectives:
keypoints:
---

```python
import pandas as pd
import matplotlib.pyplot as plt

%matplotlib inline
```


```python
url = "https://raw.githubusercontent.com/Reproducible-Science-Curriculum/automation-RR-Jupyter/gh-pages/notebooks/gapminder_cleaned.csv"
```


```python
gapminder = pd.read_csv(url)
```


```python
plt.scatter(gapminder['year'], gapminder['lifeexp'])
plt.xlabel('Year')
plt.ylabel('Life Expectancy in Years')
```




    Text(0,0.5,'Life Expectancy in Years')




![png](../fig/03-binder_plotting_4_1.png)

