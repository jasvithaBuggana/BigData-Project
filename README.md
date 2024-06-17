## Integrated Big Data Analysis of NCDC Weather Records
In this project, we'll be diving into the fascinating world of climate data and exploring some cool techniques to analyze and gain insights from it.

## What's in store? 🔍

Get ready to embark on an exciting journey through three main phases:

1. **Python**: We'll kick things off by building a nifty Python application that can extract Year and Temperature data from the original NCDC (National Climatic Data Center) records. This data will then be neatly tucked away in a text file for further processing.

   To achieve this, I developed two Python scripts: `Project_Map.py` and `Project_Reduce.py`. The mapper script extracts the Year and Temperature information from the raw data, while the reducer script aggregates and formats the data for output.

   After transferring the `CourseProjectData.zip` files to HDFS, I ran the Python application using Hadoop Streaming, specifying the input data, output directory, and the mapper and reducer scripts. The output was then copied from HDFS to the local filesystem as `js3225_output.txt`.

2. **Pig**: Next up, we'll load our freshly created text file into the powerful Pig environment. Here, we'll unleash some serious data wrangling skills to find the highest and lowest temperatures for each year. Brace yourselves for some temperature extremes!

   In the Pig environment, I loaded the `js3225_output.txt` file, grouped the records by year, and used the `MAX` and `MIN` functions to determine the highest and lowest temperatures for each year group. The results were then displayed using the `DUMP` command.

3. **Hive**: Last but not least, we'll dive into the world of Hive and use it to calculate the average temperature for each year. Get ready to uncover some fascinating temperature trends!

   In Hive, I created a table `js3225table` with the appropriate schema to match the `js3225_output.txt` file. After loading the data into the table, I used a simple `SELECT` query with the `AVG` function and `GROUP BY` clause to compute the average temperature for each year.

## Prerequisites 🛠️

Before we get started, make sure you have the following tools installed and ready to go:

- Python
- Hadoop
- Pig
- Hive


