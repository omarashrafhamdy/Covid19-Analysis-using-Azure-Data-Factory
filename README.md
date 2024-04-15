# Covid19-Analysis-using-Azure-Data-Factory

## Overview
 Built a data ingestion pipeline in Azure Data lake to Visualize Countries With Highest Corona Virus Hospital Admissions Using Azure Data Factory(ADF), Azure Data Studio, Azure Data Lake Storage Gen2, Azure SQL Database, Azure Blob Storage, Dataflow, Data Brick Transformation and Hd-insight.

## Solution Architecture
In this solution architecture, Azure Data Factory ingests ECDC and raw data into Blob Storage in Azure Data Lake Gen2, HDInsights and Databricks perform data transformation, storing results in Azure Data Lake Gen2 and Azure SQL Database respectively, with Power BI connected to Azure SQL Database for reporting and visualization of transformed data.
![image](https://github.com/omarashrafhamdy/Covid19-Analysis-using-Azure-Data-Factory/assets/58981064/aad67aee-dc80-4478-8fa6-9dd52f0b7349)

## Data Ingestion

### - Population Data

![image](https://github.com/omarashrafhamdy/Covid19-Analysis-using-Azure-Data-Factory/assets/58981064/4cbde1cc-1a78-4ce3-980b-3e062e4c2e44)

### - ECDC Data

![image](https://github.com/omarashrafhamdy/Covid19-Analysis-using-Azure-Data-Factory/assets/58981064/a48dce70-75fe-423f-9c1b-e97fe7c87d0b)

## Data Transformation

### - Cases and Deaths Data Transformation

![image](https://github.com/omarashrafhamdy/Covid19-Analysis-using-Azure-Data-Factory/assets/58981064/3d45640a-a46c-45a6-b992-c24ca02be6fd)

### - Hospital Admissions Data Transformation

![image](https://github.com/omarashrafhamdy/Covid19-Analysis-using-Azure-Data-Factory/assets/58981064/206e43a8-3e7f-4604-a531-b84f053124f7)

### - Transforming population data using pyspark

### - Transforming testing data using HIVE in HDinsight

## Data Loading

Loading required output from the transformed files in Azure SQL Database.

## Resources

[European Centre for Disease Prevention and Control (ECDC)](https://www.ecdc.europa.eu/en/data/downloadable-datasets)

[GitHub - Cloudboxacademy Covid19 Repository](https://github.com/cloudboxacademy/covid19)

[Project Use Case ](https://www.udemy.com/course/learn-azure-data-factory-from-scratch/?kw=azure+data+factory+fo+da&src=sac)
