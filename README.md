Predictive Modeling and Forecasting Consumer Trends

Overview:
This project focuses on analyzing the Consumer Price Index (CPI) and forecasting consumer expenditure trends across various product categories. Using statistical and machine learning models, the project aimed to uncover key factors driving CPI changes and predict future expenditure trends. The analysis provides insights into economic behaviors and patterns, particularly post-COVID.

Objectives:
Analyze relationships between variables influencing CPI.
Predict CPI using Linear Regression to assess key drivers.
Forecast consumer expenditure trends across product categories using SARIMAX models and Auto-ARIMA.
Highlight challenges in post-COVID trend forecasting and identify potential areas for refinement.
Tools and Libraries Used:

Python: The core programming language for analysis and modeling.
pandas: For data manipulation and preprocessing.
NumPy: For numerical computations.
scikit-learn: For building and evaluating the linear regression model.
statsmodels: For developing SARIMAX models.
matplotlib: For data visualization and trend analysis.
pmdarima: For automated ARIMA model selection (Auto-ARIMA).
Data Sources
Data was obtained from credible government and official platforms, including:
Singapore Department of Statistics (SingStat)
Data.gov.sg
Singapore Food Agency (SFA)
The data available is limited to what is publicly provided by these sources, ensuring reliability but constraining dataset size.

Methodology
Data Collection and Preprocessing

Collected data from SingStat, Data.gov.sg, and SFA.
Cleaned the data for missing values and inconsistencies.
Merged datasets to include variables like PPI, GDP per capita, SORA rates, and expenditure trends.
Exploratory Data Analysis (EDA)

Conducted visual and statistical analysis to understand relationships between variables.
Identified key factors influencing CPI trends, such as product categories, pricing, and macroeconomic indicators.
Model Development

Linear Regression: Built a predictive model to analyze key variables affecting CPI, achieving an R² of 65%.
SARIMAX Models: Developed time-series forecasting models using Auto-ARIMA loops to forecast consumer expenditure.
Addressed challenges in forecasting post-COVID price spikes, which impacted model accuracy.
Evaluation and Results

Linear regression achieved an R² of 65%, effectively explaining CPI variations based on selected features.
SARIMAX models captured overall trends but struggled with volatility caused by post-COVID data, with R² values ranging from -17 to 44%.
Models highlighted potential areas for future improvement, including alternative modeling approaches.

Key Findings:
CPI trends are influenced significantly by variables such as PPI, GDP per capita, and SORA rates.
Post-COVID expenditure trends revealed irregular spikes that traditional time-series models struggled to predict.

Challenges and Limitations:
The dataset size is limited to publicly available data from credible sources like SingStat, Data.gov.sg, and SFA.
Post-COVID data volatility introduced irregularities that SARIMAX models could not fully account for.
CPI is used here as an inflation index; however, incorporating additional data related to external economic trends might enhance accuracy further.

Future Improvements:
Expand Features: Use alternative approaches to derive more features from existing data.
Model Refinement: Experiment with more robust models such as Random Forest or XGBoost for non-linear relationships.
Address post-COVID anomalies through advanced preprocessing techniques like outlier detection.
