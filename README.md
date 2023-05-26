### Data-Engg-Casestudy - Amazon Dataset Analysis

#### Tools used:
1)Amazon S3 
2)Crawler
3)AWS Glue Data Catalouge
4)Athena
5)Sagemaker
6)MySQL

#### Execution
1.Loaded dataset to Amazon S3 bucket

2.A crawler was created to which it was connected to S3 Datastore which will infer or determine the structure of the csv file using built in classifier

3.It will creates a Metatable in the AWS Glue Data Catalog

4.After populating the data catalog an ETL job will be created to transform the csv into parquet file.

5.Mappings are applied, unwanted columns are dropped and datatypes are corrected.

6.Post tranformation the data was stored in S3 Bucket as parquet file

7.Querying file was done using Athena, MySQL, AmazonSagemaker(EDA+Visualization)
