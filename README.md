# Bangalore-Real-Estate-Data-Analysis

Overview
This repository contains an analysis of the real estate market in Bangalore, India, focusing on property prices per square foot. The dataset includes various features such as location, size, number of bedrooms (BHK), bathrooms, and pricing information.
Dataset
The dataset used for this analysis is named house_price.csv and contains the following columns:
location: The area or neighborhood of the property.
size: The type of property (e.g., BHK, Bedroom).
total_sqft: The total area of the property in square feet.
bath: The number of bathrooms in the property.
price: The total price of the property.
bhk: The number of bedrooms in the property.
price_per_sqft: The price per square foot of the property.
Analysis Goals
The primary goals of this analysis are to:
Perform exploratory data analysis (EDA) to understand the dataset's structure and key statistics.
Detect and remove outliers using various methods such as:
Mean and Standard Deviation
Percentile Method
Interquartile Range (IQR)
Z-Score Method
Visualize data distributions and relationships through plots, including box plots and scatter plots.
Check for normality in the price per square foot data and apply transformations if necessary.
Analyze correlations between numerical features using heatmaps.
Getting Started
To run this analysis locally, follow these steps:
Clone this repository:
bash
git clone https://github.com/D-K02/Bangalore-Real-Estate-Data-Analysis.git

Navigate to the project directory:
bash
cd Bangalore-Real-Estate-Data-Analysis

Install the required libraries:
bash
pip install -r requirements.txt

Run the Jupyter Notebook or Python scripts to view the analysis results.
Conclusion
This analysis provides valuable insights into Bangalore's real estate market, highlighting key factors that influence property prices. It serves as a useful resource for potential buyers, investors, and researchers interested in understanding market trends.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments
Thanks to all contributors and data sources that made this analysis possible. Your feedback and contributions are welcome!
