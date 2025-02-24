# Customer360
This is a project that uses PySpark to transform raw data into useful data on the topic of Customer 360.

The first step of the project is to load data from CSV files, parquet files.

Once the data has been loaded, PySpark will be used to clean and normalize the data. Perform data cleaning tasks to remove invalid data, handle missing values. Data preprocessing steps will include removing empty values, handling outliers, and bringing the data into a consistent format.

Next, analyses will be performed to transform raw data into useful information about customers. For example, customer information from different sources will be aggregated to create a customer 360 profile, including used time, most watch, taste, and other relevant information.

Finally, evaluate user behavior including activeness, clinginess, ... based on those metrics. Conduct EDA to gain insights into the data, explore patterns, trends, and relationships between variables.


### Data Processing:
**1. Log content**
- Log content schema:

![image](https://github.com/user-attachments/assets/a26609ce-ac06-4d4a-b726-2d6206dad9df)

- Log content raw data:

![image](https://github.com/user-attachments/assets/24b28028-271c-442a-b25d-5eca4cc1bbc4)

- Types of AppName:

![image](https://github.com/user-attachments/assets/aa11bed0-bf92-4728-a5c5-868967060593)

- Number of rows :

 ![image](https://github.com/user-attachments/assets/ad17d897-d6f3-472d-928a-200e9e35a303)

- After cleaning data:

![image](https://github.com/user-attachments/assets/e9a2f255-444d-4d50-a324-ad0da91f0bb2)

- Calculate Most watch, Taste. Calculate Type of user based on Interquartile range and from these infer activeness and clinginess:

![image](https://github.com/user-attachments/assets/59eda4a3-d69b-47c8-831b-b3625213d760)


