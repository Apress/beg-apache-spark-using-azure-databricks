# Errata for *Beginning Apache Spark Using Azure Databricks*

On **page 110** [code error]:
 
Source code needs to have a back slash at the tail end of all lines to run correctly.

Code should read:
%python
df = spark \
.read \
.option('header','True') \
.option('delimiter',',') \
.option('inferSchema','True') \
.csv('/databricks-datasets/airlines/part-00000')
]

***

On **page xx** [Summary of error]:
 
Details of error here. Highlight key pieces in **bold**.

***
