In This project I am using Pyspark, AWS and Postgres to do CLOUD etl.
there are many ways to run pyspark however I am using Google Colab because it is easy to run and there is no need for coplicated configrations, even though I have to update my spark and hadoop versions ocasionally because they keep failing me when they go outdated.

# Data source 
for this project my data is located in AWS S3 bucket that I created in my free tier account, it is accessable to the puplic, then I simply read this data as csv using spark.

# Data Transformation
As a second step I did some transformation to the data including aggregation, drop NAN and renaming some columns.

# Load Data
In the last step I loaded the data as a Dataframe into Postgres.

# Note:
if you want to run this project please try pluging the newest version of Hadoop and spark or you might get some errors!