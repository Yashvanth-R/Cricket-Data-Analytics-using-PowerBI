# Cricket-Data-Analytics-using-PowerBI 

The T20 World Cup is the pinnacle of cricket entertainment, and with web scraping, Python, and Power BI we can capture and analyze the game's data at its best.

Here's a step-by-step guide to creating a Power BI dashboard using cricket data from the T20:

## Problem Statement:
 The objective is to extract relevant information from ESPN cricinfo, clean and transform the data, and build interactive dashboards to gain insights into player performance and team strategies.

-----------------------------------------------------------

### Introduction:
The T20 Cricket World Cup recently concluded with England claiming victory over Pakistan. Now, we embark on a cricket data analytics journey using the same tournament data. Through web scraping, Python, and Pandas, we will collect and process the data, and then leverage Power BI to create engaging dashboards. The project aims to find the best players for different roles while analyzing key performance metrics for strategic decision-making.

### Web Scraping: Capturing Precious Data
Scraping  relevant data from the ESPN cricinfo website .
The scraping is performed using Parsehub Data collector, which uses a smart proxy network for seamless data collection.
Cleaning and transforming scraped data using Pandas to remove null values, format data types, and address data issues.

### Data Extraction and Cleaning
The extracted data is stored in JSON files for further processing.
The JSON files contain information such as match summaries, batting summaries, bowling summaries, and player info.

### Data Transformation and Modeling
Dataframes are processed to create a unified list of all matches.
Unnecessary columns are dropped, and data issues like special characters in player names are addressed.
A dictionary is created to capture match information, including teams and match IDs.

### Data Analysis and Visualization
Further transformations and calculations are performed using DAX measures in Power BI.
Visualizations and dashboards are created based on different player categories like power hitters and anchors.
Data modeling and DAX measures help in building the actual visuals for analysis.

### Dashboard Refinement and Final Steps
The created dashboards are refined by adding additional features and functionality.
The viewer can interact with the dashboards and make player selections based on specific criteria.

----------------------------------------------------------

## Contribute :thumbsup:
--------------------------------------
If you want to contribute in this project feel free to do that.

## Licence :scroll:
---------------------------------
MIT © [Yashvanth-R](https://github.com/Yashvanth-R)

