# L2T10 - Data Analysis Pre-processing

## Overview
In this task, we are handling categorical and missing data and data is also scaled.

## Instructions
**1. Installations**
Ensure you have Python installed on your system. You can download it from the [official Python website](https://www.python.org/).  
Install Jupyter Notebook to run the provided notebook. You can install it using pip:
```
        pip install notebook
```
**2. Running the Notebook**

+  Clone this repository to your local machine using:
```
git clone https://github.com/vswapna3202/L2T10.git
```
+  Navigate to the task's folder:
```
cd L2T10 or cd <your_task_folder>
```
+  Start Jupyter Notebook:
```
jupyter notebook
```
+  Open the Jupyter notebook named store_income_task.ipynb.

**3. Dataset:**
store_income_data_task.csv: Contains income data with columns including "country" and "date_measured" and other details.

**4. Data Analysis and Pre-processing:**  
    + *Reading Data*
        - Open the data_preprocessing.ipynb file.
        - Read in the store_income_data_task.csv file.  
    + *Display Observations*
        - Display the first five observations from the dataset.  
    + *Missing Values*
        - Get the number of missing values per column.
        - Identify the number of missing points in the first ten columns.  
    + *Analysis of Missing Data*  
    Analyse the missing data on the following three columns: store_email, department, and country.  
    Classify them according to the three categories of missingness:   
            missing completely at random (MCAR), 
            missing at random (MAR), and 
            missing not at random (MNAR)   

**5. Data Scaling:**
This task handles the normalization and standardization of variables. For more information about normalization and standardization, see [here](https://en.wikipedia.org/wiki/Normalization_(statistics)).

+ *Normalization or Standardization*
For the following examples, decide whether normalization or standardization makes more sense:
    - Building a linear regression model to predict someone's grades, given how much time they have spent on various activities during a typical school week. 
    - Include information on how students perform on several fitness tests along with student grades. Decisions on whether to normalize or standardize this variable?
          
+ *Visualizing and Scaling Data*    
    - Visualize the "EG.ELC.ACCS.ZS" column from the countries dataset using a histogram.  
    - Scale the column using the appropriate scaling method (normalization or standardization).    
    - Visualize the original and scaled data alongside each other.  