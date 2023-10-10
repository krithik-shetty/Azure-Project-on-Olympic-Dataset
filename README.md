# Azure-Project-on-Olympic-Dataset
The workflow for the following project is shown in the below image:


![Image](https://github.com/users/krithik-shetty/projects/1/assets/85822406/4d72ba3a-e294-4c6a-a34f-db6d0afb3c6d)


Raw Olympic data is ingested into the project using an Azure Data Factory pipeline. The pipeline automates data collection from the source. 


![Image](https://github.com/users/krithik-shetty/projects/1/assets/85822406/0d6c6300-0772-4794-8a87-7d817f0adc8e)


The ingested data is stored in a container with a hierarchical folder structure on Azure Data Lake Gen 2.


![Image](https://github.com/users/krithik-shetty/projects/1/assets/85822406/dcec4368-cc7d-487e-a620-08b6e668cbc1)


The data lake was then mounted to Azure Databricks. The data was transformed and then stored on Data Lake. The Databricks notebook has also been attached. 

The transformed data was linked to Azure Synapse to make further analysis.


![Image](https://github.com/users/krithik-shetty/projects/1/assets/85822406/dbe896bd-52d1-43ef-aaa8-9356ed37b193)]
