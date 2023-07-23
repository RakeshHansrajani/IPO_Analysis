# Analysis and Predictions of IPOs Listed in India from 2010 to 2023

Project Overview
This data science project focuses on the analysis and predictions of Initial Public Offerings (IPOs) listed between 2010 and 2023. The dataset includes various attributes related to IPOs, such as issue size, allocation to Qualified Institutional Buyers (QIB), High Net Worth Individuals (HNI), Retail Individual Investors (RII), issue price, listing opening price, listing closing price, listing gains, etc.

The main objectives of this project are as follows:

Data Cleaning: The initial step involves data cleaning to handle missing or incorrect values, filling zero values where appropriate, and renaming column names for better clarity.
Data Visualization: The data is visualized using various graphs and charts to gain insights and understand the distribution of different attributes.
Pre-Model Building: This step involves preprocessing the data by creating user-defined functions, encoding categorical columns, separating dependent columns, splitting the data into training and testing sets, etc.
Model Building: Different regression models are applied to predict the listing gains for IPOs based on the provided attributes.
Dataset Description
The dataset contains the following columns:

'Date': The date when the IPO was listed.
'IPO Name': The name of the IPO.
'Issue_Size': The size of the IPO issue.
'QIB': The allocation to Qualified Institutional Buyers.
'HNI': The allocation to High Net Worth Individuals.
'RII': The allocation to Retail Individual Investors.
'Total': The total allocation.
'Issue_Price': The issue price of the IPO.
'Listing_Open': The opening price of the IPO on the day of listing.
'Listing_Close': The closing price of the IPO on the day of listing.
'Listing_Gains': The percentage of listing gains on the day of listing.
Project Structure
The project repository includes the following files and directories:

data/: This directory contains the dataset files used for analysis and predictions.
images/: This directory contains images of the exploratory data analysis (EDA) part for better understanding of the data distribution.
IPO_SME_file/: This directory contains a file (IPO SME file) that others can use to practice similar analysis and modeling.
analysis_and_predictions.ipynb: The Jupyter Notebook containing the code for data cleaning, data visualization, pre-model building, and model building.
README.md: This file that provides an overview of the project, its objectives, dataset description, and project structure.
Dependencies
The following Python libraries are used in this project:

pandas
numpy
matplotlib
seaborn
scikit-learn
Make sure to install these libraries before running the code in the Jupyter Notebook.

Getting Started
To run this project on your local machine, follow these steps:

Clone or download the repository to your local machine.
Install the required Python libraries as mentioned in the Dependencies section.
Open and run the analysis_and_predictions.ipynb Jupyter Notebook to explore the analysis and modeling steps.
Acknowledgments
We would like to acknowledge the data sources and references used in this project. The dataset used for this analysis might be obtained from a specific source (mention the source if applicable). Any other references, research papers, or tutorials followed during the project are also acknowledged.

Conclusion
This project aims to provide insights into the IPO market and predict listing gains based on historical data. The results and conclusions drawn from this analysis can be valuable for investors, financial analysts, and anyone interested in the IPO market. The predictive models built in this project can serve as a basis for future predictions and decision-making.

For any questions or feedback, please feel free to contact the project contributors.

Note: This is a general template for a README file. Please modify it according to the specific details and findings of your project. Also, make sure to include the necessary credits and licenses for any external data or resources used in your project.
