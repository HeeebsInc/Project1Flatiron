# Analyzing Risk Within Movie Genres

Contributors: [Samuel Mohebban](https://github.com/HeeebsInc) and [Michael Wang]
## Packages 

```python 
import matplotlib.pyplot as plt
import pandas as pd 
import seaborn as sns
import scipy.stats as sci
import numpy as np
```

If a company is trying to enter the movie industry or create their first film, they must consider budget.  Considering movies do not have unlimited budget, you can approach this problem using a risk analaysis for each Genre.  
[Google Slide Presentation](https://docs.google.com/presentation/d/17Ba26seyYSHHLWh5TLBRsJbAz1YpsoQI2lYNyWAq4Ok/edit?usp=sharing)

## Goals


- Use existing data from [MovieLens](https://grouplens.org/datasets/movielens/) and [TMBD](https://www.kaggle.com/juzershakir/tmdb-movies-dataset) to determine if there is a difference in risk between genres
    - **Risk** is defined as the standard deviation divided by the mean
- Determine correlations between profit and budget within each genre
- Understand the distribution within each genre and whether there is noise in our dataset

## Exploratory Analysis (Plots)
### Profitable vs. Unprofitable Movies (3D Scatter Plot) 
[Functions] (Notebooks/TechnicalNotebook.ipynb)

![Scatterplot for profitable movies (budget/profit)](GitImages/scatter_profit_budget_revenue_POSITIVE[2015].png)






![Scaterplot for unprofitable movies (budget/profit)](GitImages/scatter_profit_budget_revenue_NEGATIVE[2015].png)

![Boxplot For Profit Distributions Across Genres](GitImages/BoxPlot_genres_2010.png)

