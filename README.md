# Deep Learning and Machine Learning Tasks

## Usefull Tools
[![USEFULL TOOLS](https://skillicons.dev/icons?i=python,tensorflow,vscode)](https://skillicons.dev)

## Some Usefull Code

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
reviews.<LABEL>.unique()
```

- Get sum of all the label
```
df.<LABEL>.value_counts()
```

- Convert spesific pandas dataframe to numpy array
```
df.iloc[:, :-1].values
```

- One Hot Encoding by pandas
```
pd.get_dummies(<VARIABLE>)
```

- Auto multi color scatter plot using seaborn
```
sns.seaborn(x, y, hue=<LABEL_VARIABLE>)
```

- Create data
```
make_classification(n_features=<JUMLAH_KOLOM>, n_classes=<JUMLAH_CLASS>)
```
