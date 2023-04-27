# Ex03-Univariate-Analysis

## Aim: 
To read the given data and perform the univariate analysis with different types of plots.

### Theory:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

### Algorithm:

## Step 1:

Read the given data.

## Step 2:

Get the information about the data.

## Step 3:

Remove the null values from the data.

## Step 4:

Mention the datatypes from the data.

## Step 5:

Count the values from the data.

## Step 6:

Do plots like boxplots,countplot,distribution plot,histogram plot.

## Program:
```
Program developed by : Thanika sree B 
Register number : 212222100055
import pandas as pd import numpy as np import seaborn as sns
data=pd.read_csv('SuperStore.csv') data
data.head()
data.info()
data.describe()
data.isnull().sum()
data.dtypes
data['Postal Code'].value_counts()
sns.boxplot(x='Postal Code', data=data)
sns.countplot(x='Postal Code',data=data)
sns.distplot(data["Postal Code"])
sns.histplot(x='Postal Code',data=data)
```
## Output:
## Dataset:
![exp3ds1](https://user-images.githubusercontent.com/119557910/234943000-f032f529-6db4-428a-ae5d-ef2dc272acf7.png)

## Head data:
![exp3ds2](https://user-images.githubusercontent.com/119557910/234943329-ec08a162-bace-4bcf-a43f-246a02dafd7e.png)

## Dataset Information:
![exp3ds3](https://user-images.githubusercontent.com/119557910/234943480-9510eae5-2220-441e-aee8-cc7e9169f69c.png)

## Data Description:
![dsss](https://user-images.githubusercontent.com/119557910/234943701-68d73978-3b23-4ae9-b919-4b4f3be2a491.png)

## Null data:
![dsssss](https://user-images.githubusercontent.com/119557910/234943831-1a461f90-82db-4710-a4e2-f310fa007ca8.png)

## Datatype:
![than0](https://user-images.githubusercontent.com/119557910/234944034-05ebfc49-91a3-46c3-a93a-7fa32ee903c9.png)

## Value counts:
![ooo](https://user-images.githubusercontent.com/119557910/234944339-14cf0350-1d6f-47f4-acd9-a553fbf153c2.png)

## Box plot:
![ppp](https://user-images.githubusercontent.com/119557910/234944647-873be677-9228-406b-bb38-b1f727c9f82b.png)

## Count plot:
![hhh](https://user-images.githubusercontent.com/119557910/234944994-7b82f0f8-cdcf-4e33-983e-097aec25aed5.png)

## Distribution plot:
![rrrr](https://user-images.githubusercontent.com/119557910/234945276-b127c374-4007-4f5e-b4ed-ab6379981db7.png)

## Histogram plot:
![ww](https://user-images.githubusercontent.com/119557910/234945615-6a8ed42b-82ec-48ba-97ae-72adbbdecacd.png)

## Result:

Thus, we have read the given data and performed the univariate analysis with different types of plots.








