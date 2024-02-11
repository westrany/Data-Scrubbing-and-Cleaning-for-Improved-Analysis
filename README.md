![image](https://github.com/westrany/Data-Scrubbing-and-Cleaning-for-Improved-Analysis-with-DataCleaner/assets/69496007/17e7147a-969f-4717-a7e2-f04e9084f65a)# Data Scrubbing and Cleaning for Improved Analysis with DataCleaner

![image](https://github.com/westrany/Data-Scrubbing-and-Cleaning-for-Improved-Analysis-with-Python/assets/69496007/8b8c009c-dcb5-4c1e-bcb8-cc3821423902)

## Objective  

Demonstrate proficiency in data cleaning techniques using DataCleaner, a third-party library based on Pandas DataFrame that employs a distinctive method, merging conventional data cleaning processes and automating them, resulting in significant time and effort savings.  

The project aims to prepare raw datasets for analysis by addressing inconsistencies, missing values, outliers, and other data quality issues.

## Dataset Selection  

The dataset chosen for this project is an unclean copy of my GoodReads dataset (as for 2024/02/11) in csv format with 386 entries. Data types included are integers, floats, strings, data/time and booleans (both in TRUE/FALSE and 0/1 formats). The following table illustrates each section, its data type and entry example:  

| Column Title                  | Data Type      | Example                                                        |
|-------------------------------:|:----------------:|:----------------------------------------------------------------:|
| Book Id                       | Integer        | 50617439                                                       |
| Title                         | String         | Poetry Scraps                                                  |
| Author                        | String         | Rowan Skye                                                     |
| Author l-f                    | String         | Skye, Rowan                                                    |
| Additional Authors            | String         | Miguel Serras Pereira                                          |
| ISBN                          | String         | 9896419884                                                     |
| ISBN13                        | String         | 9789896419882                                                  |
| My Rating                     | Float          | 5                                                              |
| Average Rating                | Float          | 4.3                                                              |
| Publisher                     | String         | Relógio D'Água Editores                                        |
| Binding                       | String         | Paperback                                                      |
| Number of Pages               | Integer        | 152                                                            |
| Year Published                | Integer        | 2020                                                           |
| Original Publication Year     | Integer        | 2005                                                           |
| Date Read                     | Date (DD-MM-YYYY)         | 22/01/2024                                          |
| Date Added                    | Date (DD-MM-YYYY)          | 30/01/2024                                         |
| Bookshelves                   | String         | to-read                                                        |
| Bookshelves with positions    | String         | to-read (#179)                                                 |
| Exclusive Shelf               | String         | to-read                                                        |
| My Review                     | String         | Mind-blown in space                                            |
| Spoiler                       | Boolean (String)         | FALSE                                                |
| Private Notes                 | String         | gift from Hufflepuff                                           |
| Read Count                    | Integer        | 3                                                              |
| Owned Copies                  | Boolean (Integer)        | 1                                                    |  

This is a good dataset to clean and analyse as it contains missing values, inconsistent formats and outliers. Since GoodReads notifies you when there are duplicate entries, which meant I had no duplicate entires, I asked an AI to add 20 random duplicate entries to the data set for the purpuse of this project.

## Tools  

• DataCleaner library for data manipulation and cleaning.

## Key Steps  

1. **Data Collection:** Download the chosen datasets and load them into the Python environment.
   
2. **Initial Data Assessment:**
   
      • Explore the structure of the datasets (columns, data types, size)
   
      • Check for missing values, duplicate entries, and outliers.
   
      • Identify any inconsistencies or errors in data formats.
   
3. **Data Cleaning:**
   
      • Use DataCleaner's functionality to replace missing values with the mode or median on a column-wise basis.
   
      • Encode categorical variables using appropriate methods provided by DataCleaner.  

      • Remove rows with missing values using DataCleaner's automated features.  

      • Apply automatic discovery and correction of common data issues such as outliers and format errors using DataCleaner's built-in algorithms.  

   
4. **Data Transformation:**
   
      • Perform data transformations as necessary (e.g., normalization, log transformation), leveraging DataCleaner's capabilities.
   
      • Create derived features or variables that might enhance analysis.
   
8. **Data Validation:**
   
      • Validate the cleaned datasets to ensure that data quality issues have been addressed effectively.
   
      • Use DataCleaner's data quality assessment metrics and methods to assess data completeness, accuracy, consistency, etc.
   
      • Check for any unintended consequences of data cleaning operations.
   
10. **Documentation and Reporting:**
    
      • Document the data cleaning process, including the steps taken and rationale behind decisions, utilizing DataCleaner's visual interface if applicable.
    
      • Present summary statistics and visualizations to illustrate the improvements in data quality.
    
      • Prepare a report highlighting the impact of data cleaning on the analysis potential of the datasets.
    

## Additional Considerations  
1. Ensure reproducibility by documenting all code and steps taken in the cleaning process.
   
2. Consider leveraging DataCleaner's visual interface for easier data management and exploration.
   
3. Utilize DataCleaner's extensibility to integrate with other data processing and analysis tools if necessary.

## Conclusion  

By completing this project using DataCleaner, you will showcase your ability to efficiently address data quality issues and prepare datasets for analysis, demonstrating key skills valued in the field of data science.  


This project structure adheres to the principles of clear objectives, high-quality data, robust algorithms, interpretability, continuous improvement, cross-functional collaboration, and ethical considerations outlined in the guidelines, while leveraging the unique features of DataCleaner for data cleaning and transformation.  

## Research and Sources   

[My Favorite Python Libraries for Data Cleaning in 2023](https://medium.com/@tubelwj/my-favorite-python-libraries-for-data-cleaning-in-2023-c475830dacbb)
