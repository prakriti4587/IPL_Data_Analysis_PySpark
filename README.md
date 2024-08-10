**Overview**
This project focuses on analyzing the Indian Premier League (IPL) data from the 2017 season. The analysis was conducted using AWS S3 for data storage, Databricks for computation, and PySpark for data processing. The project aims to uncover interesting insights and patterns in the IPL matches using big data technologies.

**Architecture Diagram**
![image](https://github.com/user-attachments/assets/733300d1-9c3b-407d-a870-875168e5e423)

The dataset used in this project is from the IPL 2017 season, and it includes detailed information about each match, player statistics, and team performances.

**Technologies**
**Amazon S3 Bucket**:
Used for storing the IPL dataset. The data is uploaded to an S3 bucket and accessed directly from there.
![image](https://github.com/user-attachments/assets/6c4abf61-c5c1-4cfc-ab74-43460b3c3bcf)

**Databricks**: 
The primary platform used for data processing and analysis. Databricks notebooks were used to write and execute **PySpark** code.
Before you can run any code in Databricks, you'll need to connect to a cluster. A cluster in Databricks is a group of computational resources that you can use to execute your data processing tasks.

The analysis covers various aspects of the IPL 2017 season, including:

Top Performers: Identifying the best players based on runs scored, wickets taken, etc.
Winning Strategies: Analyzing match outcomes to determine key factors contributing to wins.
Team Analysis: Comparing team performances throughout the season.

