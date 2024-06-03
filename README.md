# SharePoint-Migration

# Introduction
This process is to compare data coming from a data lake system to sharepoint and measuring scalability and cost management for the nearest future
In the architecture, we read the data from azure databricks verifying the file type and sending the data into specified share point folder. also we wrote a fucntion to refresh access token to run daily and whcih gives acccess to the sharepoint url directory daily.
we also created a customer connector hat enables us to connect to databricks to orchestrate our workflow. For References check https://medium.com/@poojaanilshinde/create-azure-logic-apps-custom-connector-for-azure-databricks-e51f4524ab27

# Tools Used
1. Azure Databricks
2. Spark
3. Azure Logic :Azure Logic Apps is a cloud service that helps you schedule, automate, and orchestrate tasks, business processes, and workflows when you need to integrate apps, data, systems, and services across enterprises or organisations. 
4. Data Lake:ALDS


# Data Architecture
![Screenshot (24)](https://github.com/adunajiye/SharePoint-Migration/assets/80220180/ff503e7c-1e40-4304-9b98-c99331394e72)
