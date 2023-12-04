# Individual Project #3: Databricks ETL (Extract Transform Load) Pipeline


## Overview
This project leverages Databricks to implement an ETL (Extract, Transform, Load) pipeline, primarily utilizing Spark SQL and Delta Lake. The objective is to demonstrate a comprehensive understanding of data processing and management within a cloud-based architecture. The purpose of this project is to perform ETL operations with a pipeline on Databricks using Spqrk SQL.

## Key Components

### 1. Databricks Notebook for ETL Operations
- **Location**: Azure Workspace 
- **Objective**: To extract data from a CSV file (`forbes_2022_billionaires.csv`), apply transformations, and store the results in Delta Lake.
- **Key Steps**:
  - Extraction: Loading data into a Spark DataFrame.
  - Transformation: Filtering and refining the data.
  - Loading: Saving the processed data in Delta format.
- **Visualization**: Step-wise ETL process diagrams are provided for clarity ([Ingestion](https://github.com/nogibjj/Individual_Project3_Ayush/blob/main/Images/ingestion.png), [Transform](https://github.com/nogibjj/Individual_Project3_Ayush/blob/main/Images/transform.png), [Load](https://github.com/nogibjj/Individual_Project3_Ayush/blob/main/Images/Load.png)).

### 2. Utilizing Spark SQL for Data Transformations
- **Notebook**: `03_Spark_SQL_For_DataTransformation.py`
- **Features**:
  - Efficient handling of distributed datasets.
  - Advanced analytics capabilities.
  - Integration with various data formats.
  - Enhanced scalability and performance.
- **Functionality**: The notebook performs SQL-based transformations on Delta tables and incorporates error handling mechanisms.
- **Visual Aid**: [Spark SQL Operations](https://github.com/nogibjj/Individual_Project3_Ayush/blob/main/Images/Pyspark%20Transformation%20and%20Error%20handling.png)

### 3. Error Handling and Data Validation
- **Implementation**: Consistent error handling and validation checks are integrated within each step of the ETL process.

### 4. Data Storage with Delta Lake
- **Notebook**: `02_Delta_Lake_For_Storage.py`
- **Advantages**:
  - ACID transactions for reliable data updates.
  - Time-travel feature for historical analyses.
  - Schema evolution and optimized query performance.
- **Process**: The notebook reads, transforms, and stores data in Delta Lake, ensuring robust error handling throughout.
- **Illustration**: [Delta Lake Storage](https://github.com/nogibjj/Individual_Project3_Ayush/blob/main/Images/DeltaLakeStorage.png)

### 5. Visualization of Transformed Data
- **Notebook**: `04_Visualization_of_Transformed_Data.py`
- **Functionality**: Generates insightful visualizations using Matplotlib and Plotly from the transformed Delta table.
- **Output**: The visualizations are saved and can be viewed in the Azure workspace.
- **Example**: [Data Visualization](https://github.com/nogibjj/Individual_Project3_Ayush/blob/main/Images/Visualization.png)

### 6. Automated Pipeline Trigger
- **Schedule**: Configured to initiate daily at 04:10:00.
- **Workflow**: Depicts the entire pipeline process, including table creation, data transformation, and visualization.
- **Workflow Diagrams**: [Pipeline Workflow](https://github.com/nogibjj/Individual_Project3_Ayush/blob/main/Images/workflow_pipeline.png), [Successful Run](https://github.com/nogibjj/Individual_Project3_Ayush/blob/main/Images/Workflow.png)



## Demonstration
- **Video Demo**: A concise walkthrough of the project is available on YouTube ([Watch Demo](https://www.youtube.com/watch?v=ZXVcCGPI3Us)).
