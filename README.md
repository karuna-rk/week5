import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv('C:/Users/Admin/Downloads/archive (7)/House_Price.csv',header=0)
df.head()

df.shape

df.describe()

sns.jointplot(x='n_hot_rooms',y='price',data=df)

sns.jointplot(x='rainfall',y='room_num',data=df)

sns.jointplot(x='parks',y='room_num',data=df)

sns.countplot(x="waterbody",data=df)

sns.countplot(x="bus_ter",data=df)


 
