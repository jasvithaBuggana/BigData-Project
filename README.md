#### Project Overview

In this project, I delved into the realm of climate data analysis, utilizing the extensive records provided by the National Climatic Data Center (NCDC). My goal was to extract, process, and derive meaningful insights from these records using a variety of powerful tools and techniques.

#### Project Phases

1. **Data Extraction with Python and Hadoop**
   - I started the project by developing Python scripts (`Project_Map.py` and `Project_Reduce.py`) to extract year and temperature data from raw NCDC records. Using Hadoop Streaming, I efficiently processed large datasets and stored the results for further analysis.

2. **Data Wrangling with Pig**
   - Moving into the Pig environment, I loaded the preprocessed data and leveraged its data wrangling capabilities. Here, I focused on finding the highest and lowest temperatures recorded for each year, employing aggregation functions (`MAX` and `MIN`) to uncover key insights.

3. **Statistical Analysis with Hive**
   - Finally, utilizing Hive, I established a structured data table (`js3225table`) to facilitate detailed statistical analysis. By computing the average temperature for each year using the `AVG` function and grouping by year, I revealed long-term temperature trends and patterns.

#### Tools Required

- **Python**: Essential for initial data extraction and preprocessing.
- **Hadoop**: Provided the distributed computing framework necessary for handling large-scale data processing.
- **Pig**: Enabled flexible data manipulation and aggregation, crucial for deriving specific insights.
- **Hive**: Facilitated structured querying and analysis of data stored in the Hadoop Distributed File System (HDFS), ideal for statistical calculations and trend identification.

#### Conclusion

Through this project, I showcased the capabilities of modern data analytics tools and uncovered valuable climate trends and patterns hidden within the vast NCDC records. By following these phases, I empowered researchers and climate enthusiasts alike to explore and interpret significant climate data with precision and efficiency. This project not only demonstrated technical proficiency in handling large datasets but also contributed to the understanding of long-term climatic changes.
