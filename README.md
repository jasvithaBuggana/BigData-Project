### Climate Data Analysis Using NCDC Records

#### Project Overview

In this project, we delve into the realm of climate data analysis, utilizing the extensive records provided by the National Climatic Data Center (NCDC). Our goal is to extract, process, and derive meaningful insights from these records using a variety of powerful tools and techniques.

#### Project Phases

1. **Data Extraction with Python and Hadoop**
   - We kickstart the project by developing Python scripts (`Project_Map.py` and `Project_Reduce.py`) to extract year and temperature data from raw NCDC records. Using Hadoop Streaming, we efficiently process large datasets and store the results for further analysis.

2. **Data Wrangling with Pig**
   - Moving into the Pig environment, we load our preprocessed data and leverage its data wrangling capabilities. Here, we focus on finding the highest and lowest temperatures recorded for each year, employing aggregation functions (`MAX` and `MIN`) to uncover key insights.

3. **Statistical Analysis with Hive**
   - Finally, utilizing Hive, we establish a structured data table (`js3225table`) to facilitate detailed statistical analysis. By computing the average temperature for each year using the `AVG` function and grouping by year, we reveal long-term temperature trends and patterns.

#### Tools Required

- Python: Essential for initial data extraction and preprocessing.
- Hadoop: Provides the distributed computing framework necessary for handling large-scale data processing.
- Pig: Enables flexible data manipulation and aggregation, crucial for deriving specific insights.
- Hive: Facilitates structured querying and analysis of data stored in Hadoop Distributed File System (HDFS), ideal for statistical calculations and trend identification.

#### Conclusion

Through this project, we aim to not only showcase the capabilities of modern data analytics tools but also to uncover valuable climate trends and patterns hidden within the vast NCDC records. By following these phases, we empower researchers and climate enthusiasts alike to explore and interpret significant climate data with precision and efficiency.

---

Feel free to adjust the details further based on your project specifics and achievements!
