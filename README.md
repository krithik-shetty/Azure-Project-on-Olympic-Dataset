# Azure-Project-on-Olympic-Dataset
The workflow for the following project is shown in the below image:

![77811739556](https://github.com/krithik-shetty/Azure-Project-on-Olympic-Dataset/assets/85822406/f2112a59-9de6-4bae-bb96-ba177a9c31cf)


Raw Olympic data is ingested into the project using an Azure Data Factory pipeline. The pipeline automates data collection from the source. 

![pipeline](https://github.com/krithik-shetty/Azure-Project-on-Olympic-Dataset/assets/85822406/64156fe4-31c8-4a80-b6f4-5817f1e8c006)


The ingested data is stored in a container with a hierarchical folder structure on Azure Data Lake Gen 2.

![Raw_data](https://github.com/krithik-shetty/Azure-Project-on-Olympic-Dataset/assets/85822406/53e6720e-13e7-4b11-a05d-47584efcf1e8)

The data lake was then mounted to Azure Databricks. The data was transformed and then stored on Data Lake. The Databricks notebook has also been attached. 

The transformed data was linked to Azure Synapse to make further analysis.

![Synapse](https://github.com/krithik-shetty/Azure-Project-on-Olympic-Dataset/assets/85822406/94cd9c40-64cb-40ee-a2a4-ef670f9b5e14)
