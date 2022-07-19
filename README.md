# Amex default prediction
Link to kaggle: 
https://www.kaggle.com/competitions/amex-default-prediction

## Data
Download test and train data from the link since the files are too big.

https://www.kaggle.com/competitions/amex-default-prediction/data?select=train_data.csv

https://www.kaggle.com/competitions/amex-default-prediction/data?select=test_data.csv

## Use Spark on Colab
open a notebook

```
!pip install py4j pyspark
from pyspark.sql import SparkSession
spark = SparkSession.builder.getOrCreate()
spark = SparkSession.builder.appName('dma').getOrCreate()
```