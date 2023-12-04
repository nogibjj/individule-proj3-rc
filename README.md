# Individual Project #3: Databricks ETL (Extract Transform Load) Pipeline


## Overview
This project leverages Databricks to implement an ETL (Extract, Transform, Load) pipeline, primarily utilizing Spark SQL and Delta Lake. The objective is to demonstrate a comprehensive understanding of data processing and management within a cloud-based architecture. The purpose of this project is to perform ETL operations with a pipeline on Databricks using Spqrk SQL.

## Key Components

### 1. Databricks Notebook for ETL Operations
- **Location**: Azure Workspace 
- **Objective**: To extract data from a CSV file [forbes_2022_billionaires.csv](https://www.kaggle.com/datasets/prasertk/forbes-worlds-billionaires-list-2022), apply transformations, and store the results in Delta Lake.
- **Key Steps**:
  - Extraction: Loading data into a Spark DataFrame.

<img width="1074" alt="Screenshot 2023-12-04 at 09 57 44" src="https://github.com/nogibjj/individule-proj3-rc/assets/123079408/a9a696a4-0c40-43f0-aacf-7dd17136a655">

  - Transformation: Filtering and refining the data.
  
<img width="985" alt="Screenshot 2023-12-04 at 09 54 00" src="https://github.com/nogibjj/individule-proj3-rc/assets/123079408/77c38ca6-4c73-44e2-b1fa-2ef4bf11bad9">

  - Loading: Saving the processed data in Delta format.

 <img width="1303" alt="Screenshot 2023-12-04 at 09 53 02" src="https://github.com/nogibjj/individule-proj3-rc/assets/123079408/421cc7ec-7099-4b4f-909b-17fc012b6861">

  
### 2. Utilizing Spark SQL for Data Transformations
- **Notebook**: `Transformation.py`
- **Features**:
  - Efficient handling of distributed datasets.
  - Advanced analytics capabilities.
  - Integration with various data formats.
  - Enhanced scalability and performance.
- **Functionality**: The notebook performs SQL-based transformations on Delta tables and incorporates error handling mechanisms.

### 3. Error Handling and Data Validation
- **Implementation**: Consistent error handling and validation checks are integrated within each step of the ETL process.

### 4. Data Storage with Delta Lake
- **Notebook**: `Storage.py`
- **Advantages**:
  - ACID transactions for reliable data updates.
  - Time-travel feature for historical analyses.
  - Schema evolution and optimized query performance.
- **Process**: The notebook reads, transforms, and stores data in Delta Lake, ensuring robust error handling throughout.

  <img width="781" alt="Screenshot 2023-12-04 at 10 02 56" src="https://github.com/nogibjj/individule-proj3-rc/assets/123079408/1016cf9e-2782-47c2-9293-6480ad863eb7">


### 5. Visualization of Transformed Data
- **Notebook**: `Visualization.py`
- **Functionality**: Generates insightful visualizations using Matplotlib and Plotly from the transformed Delta table.
- **Output**: The visualizations are saved and can be viewed in the Azure workspace.

<img width="636" alt="Screenshot 2023-12-04 at 10 08 52" src="https://github.com/nogibjj/individule-proj3-rc/assets/123079408/20fe9693-68b1-42d3-9d2a-b7b76f049bde">


### 6. Automated Pipeline Trigger
- **Schedule**: Configured to initiate daily at 04:10:00.
- **Workflow**: Depicts the entire pipeline process, including table creation, data transformation, and visualization.
- **Workflow Diagrams**:

  <img width="1014" alt="Screenshot 2023-12-04 at 09 42 37" src="https://github.com/nogibjj/individule-proj3-rc/assets/123079408/ab4e76de-32eb-4917-9ff2-e0f7d5d8f796">

  <img width="990" alt="Screenshot 2023-12-04 at 09 38 09" src="https://github.com/nogibjj/individule-proj3-rc/assets/123079408/19e9f2c7-420c-4eb0-a7a0-cb51ebfb4928">



## Demonstration
- **Video Demo**: A concise walkthrough of the project is available here. ([Watch Demo](https://prodduke-my.sharepoint.com/:v:/r/personal/rc381_duke_edu/Documents/idsproj3.mov?csf=1&web=1&e=bpZU0X&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D).
