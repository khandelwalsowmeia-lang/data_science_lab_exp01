# data_science_lab_exp01# data_science_lab_exp01
import pandas as pd
df=pd.read_csv('/content/sample_data/california_housing_test.csv')
df.head(10)
df.info()
df.isnull().sum()
