# prophet_challenge

README
A Time Series Analysis of Mercado Libre's Google Search Trend and Stock Price Data

Introduction
This project aims to determine if the ability to predict Google search traffic can translate into the ability to successfully trade Mercado Libre's stock. The analysis involves visualizing the data's seasonality, evaluating the correlation between stock price and Google search traffic, and using Facebook's Prophet to forecast search traffic and future revenue.

Table of Contents
Introduction
Data Collection
Data Preprocessing
Data Visualization
Correlation Analysis
Forecasting with Prophet
Results
Conclusion
How to Run the Project
Dependencies
Author
Data Collection
The data for this project was collected from the following sources:

Google Trends: For search traffic data related to Mercado Libre.
Stock Market: For Mercado Libre's stock price data.
Data Preprocessing
Cleaning: Removing any missing or irrelevant data points.
Normalization: Standardizing the data to ensure consistency.
Resampling: Adjusting the data frequency to match the time series requirements.
Data Visualization
The data's seasonality was visualized using various plotting techniques to identify patterns and trends. This includes:

Line plots of the raw data.
Seasonal decomposition plots to separate the trend, seasonal, and residual components.
Correlation Analysis
The relationship between Mercado Libre's stock price and its Google search traffic was evaluated using correlation coefficients. This analysis helps in understanding the strength and direction of the relationship.

Forecasting with Prophet
Facebook's Prophet was used to build a machine learning model to forecast:

Google Search Traffic: Predict future search trends.
Revenue: Project future company revenue based on search trends.
Results
The results section includes:

Visualizations of the forecasted search traffic and revenue.
Insights gained from the correlation analysis.
Evaluation of the model's performance and accuracy.
Conclusion
Summarize the findings of the analysis and discuss whether the ability to predict Google search traffic can be translated into successful stock trading for Mercado Libre.

How to Run the Project
Clone the repository:

Copy code
git clone https://github.com/yourusername/mercado-libre-analysis.git
cd mercado-libre-analysis
Install dependencies:

Copy code
pip install -r requirements.txt
Run the analysis:

Copy code
jupyter notebook
Open mercado-libre-analysis.ipynb and run all cells.

Dependencies
Python 3.x
Jupyter Notebook
pandas
numpy
matplotlib
seaborn
fbprophet

Author:
Kathryn Kavanagh
katiekavanagh21@gmail.com

