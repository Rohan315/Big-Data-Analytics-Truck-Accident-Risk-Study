# Big-Data-Analytics-Truck-Accident-Risk-Study
Using the Cloudera Hadoop tools and techniques to process the data and create our own analytics reports / visual presentation that will benefit decision-makers.
Truck-Accidents-Risk-Study

### Project Objective

Big Data Hadoop Ecosystems will use truck fleet data to refine and analyze trucking movement to meet the organizational goal of better understanding risk. The use case involves geographic data, vehicles, average mileage, gas consumption, events, risk factors, and other supporting information. Each truck has been equipped to with devices to log location and event data. These events are streamed back to a datacenter where we will process the data and revise truck movements to increase safety.

### Business Objective

Accidents caused by large trucks remain one of the leading causes of injuries and deaths in the United States. The objective is identifying dangerous commercial truck drivers nationwide. Upon completing this study, we will be able to answer common business questions related to the trucking business, such as: Which truck has the highest risk factor based on geographic location and time?

### Tools Used

Storage: Cloudera Hadoop, HDFS

Data Modeling and ETL: Hive, Impala, and Pig

Data Visualization: Tableau

### Tasks

Task 1: Loading Data into Hadoop File System (HDFS)

Objectives

In this exercise, we will load the geographic data we created in your local machine into HDFS, which is in Cloudera VM. We can perform tasks like create directories, navigate file systems, and upload files to HDFS. In addition, we will perform a few other HIVE related tables loading tasks. Outlines

Transfer your input files into Cloudera VM by utilizing the system copy command.
Create a Hive Table for geolocation tab and load data from Geolocation file.
Loaded the imported file into HIVE by utilizing “LOAD DATA INPATH”.
Task 2: Integrating HDFS with Tableau via JDBC drivers for Impala and Hive

Objectives

In this exercise, we will be integrating HDFS instance including the tables with an external analytical tool. Then we can perform some analytics or calculations, creating visualizations or dashboard if needed.

Outlines

Identify the correct driver
Install the JDBC driver
Load the tables into the analytical tools via ETL transactions
Create the Charts needed.
Step 1:

Go to the URL https://www.cloudera.com/downloads.html
Download Impala ODBC Drive only.
Step 2: Install ODBC for Impala.

Step 3: Connect to HDFS using Cloudera Hadoop connection in Tableau.
