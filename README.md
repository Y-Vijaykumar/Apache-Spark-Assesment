# Apache-Spark-Assesment
!pip install pyspark
import pyspark 
from pyspark.sql import SparkSession
Session = SparkSession.builder.appName('SparkSession').getOrCreate
Session
import pandas as pd
df1 = spark.read_csv('people.csv')
df1
df1.to_parquet()
df1.shape
