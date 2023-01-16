# Some Usefull Code

- Count missing value of data <br>
```
dataFrame.isna().sum()
```

- Create some condition and get the index to make it a new dataFrame <br>
Dataset (Kaggle) : [winemag-data-130k-v2.csv](https://www.kaggle.com/datasets/zynicide/wine-reviews) <br>
```
italian_wines = reviews.loc[reviews.country == 'Italy']
top_oceania_wines = reviews.loc[(reviews.country.isin(['Australia', 'New Zealand'])) & (reviews.points >= 95)]
```

- Get all unique value of columns
```
reviews.country.unique()
```

- Get number of label and its destribution
```
df.<column_name>.value_counts()
```
