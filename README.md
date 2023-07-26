# Analysis and Predictions of IPOs

### Project Overview
This data science project focuses on the analysis and predictions of Initial Public Offerings (IPOs) listed between 2010 and 2023. The dataset includes various attributes related to IPOs, such as issue size, allocation to Qualified Institutional Buyers (QIB), High Net Worth Individuals (HNI), Retail Individual Investors (RII), issue price, listing opening price, listing closing price, listing gains, etc.

The main objectives of this project are as follows:
* Data Cleaning: The initial step involves data cleaning by renaming column names for better clarity, to handle missing or incorrect values, filling zero values with appropriate ones, changing datatypes from object to float, and extracting year, month and day from date column for further analysis.
* Data Visualization: The data is visualized using various graphs and charts to gain insights and understand the distribution of different attributes and its relation with listing price and heatmap to visualize relation between all the attributes.
* Pre-Model Building: This step involves preprocessing the data by creating user-defined functions, encoding categorical columns, separating dependent columns, splitting the data into training and testing sets, etc.
* Model Building: Different regression models are applied to predict the listing gains for IPOs based on the provided attributes.


### Dataset Description
The dataset contains the following columns:

1. 'Date': The date when the IPO was listed.
2. 'IPO Name': The name of the IPO.
3. 'Issue_Size': The size of the IPO issue.
4. 'QIB': The allocation to Qualified Institutional Buyers.
5. 'HNI': The allocation to High Net Worth Individuals.
6. 'RII': The allocation to Retail Individual Investors.
7. 'Total': The total allocation.
8. 'Issue_Price': The issue price of the IPO.
9. 'Listing_Open': The opening price of the IPO on the day of listing.
10. 'Listing_Close': The closing price of the IPO on the day of listing.
11. 'Listing_Gains': The percentage of listing gains on the day of listing.

### Project Structure
The project repository includes the following files and directories:

* IPOs.xlsx: This directory contains the dataset files used for analysis and predictions.
* Visualisaton_Images/: This directory contains images of the exploratory data analysis (EDA) part for a better understanding of the data distribution.
* IPO_sme.xlsx: This data set is for SME IPOs which can be used to practice similar analysis and modeling.
* IPO_Analysis.ipynb: The Jupyter Notebook containing the code for data cleaning, data visualization, pre-model building, and model building.
* README.md: This file provides an overview of the project, its objectives, dataset description, and project structure.

### Conclusion
This project aims to provide insights into the IPO market and predict listing gains based on historical data. The results and conclusions drawn from this analysis can be valuable for investors, financial analysts, and anyone interested in the IPO market. The predictive models built in this project can serve as a basis for future predictions and decision-making.

