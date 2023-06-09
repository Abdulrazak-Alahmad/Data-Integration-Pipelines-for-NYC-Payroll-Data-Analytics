## Project: Data Integration Pipelines for NYC Payroll Data Analytics
The City of New York would like to develop a Data Analytics platform on Azure Synapse Analytics to accomplish two primary objectives:

Analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.
Make the data available to the interested public to show how the City’s budget is being spent on salary and overtime pay for all municipal employees.
You have been hired as a Data Engineer to create high-quality data pipelines that are dynamic, can be automated, and monitored for efficient operation. The project team also includes the city’s quality assurance experts who will test the pipelines to find any errors and improve overall data quality.

The source data resides in Azure Data Lake and needs to be processed in a NYC data warehouse in Azure Synapse Analytics. The source datasets consist of CSV files with Employee master data and monthly payroll data entered by various City agencies.


## Instructions
The below diagram shows the project architecture.  
- Step 1: Prepare the Data Infrastructure.
- Step 2: Create Linked Services
- Step 3: Create Datasets in Azure Data Factory
- Step 4: Create Data Flows
- Step 5: Data Aggregation and Parameterization
- Step 6: Get Data analysis from Synapse SQL DW.


### pipeline_load_payroll_data_2021.

![pipeline_load_payroll_data_2021](Screenshots/pipeline_load_payroll_data_2021.jpeg "pipeline_load_payroll_data_2021.jpeg")

### pipeline_master_load_succeeded

![pipeline_master_load_succeeded](Screenshots/pipeline_master_load_succeeded.jpeg "pipeline_master_load_succeeded.jpeg")

 ### global_parameter

 ![global_parameter](Screenshots/global_parameter.jpeg "global_parameter.jpeg")
 
### aggregate_data_flows.

![aggregate_data_flows](Screenshots/aggregate_data_flows.jpeg "aggregate_data_flows.jpeg")

### aggregate_pipeline.

![aggregate_pipeline](Screenshots/aggregate_pipeline.jpeg "aggregate_pipeline.jpeg")
