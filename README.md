# Customer360
This is a project that uses PySpark to transform raw data into useful data on the topic of Customer 360.

The first step of the project is to load data from CSV files, parquet files.

Once the data has been loaded, PySpark will be used to clean and normalize the data. Perform data cleaning tasks to remove invalid data, handle missing values. Data preprocessing steps will include removing empty values, handling outliers, and bringing the data into a consistent format.

Next, analyses will be performed to transform raw data into useful information about customers. For example, customer information from different sources will be aggregated to create a customer 360 profile, including used time, most watch, taste, and other relevant information.

Finally, evaluate user behavior including activeness, clinginess, ... based on those metrics. Conduct EDA to gain insights into the data, explore patterns, trends, and relationships between variables.