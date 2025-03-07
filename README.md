# customer_churn_prediction
Customer Churn Prediction This project focuses on analyzing customer data to predict churn rates using Python. It involves data cleaning, feature engineering, exploratory data analysis (EDA), and data visualization to uncover key factors influencing customer retention. 
## Customer Churn Analysis
### Project Overview
This project aims to analyze customer churn behavior using Python and Pandas. The goal is to
understand why customers are leaving, identify key factors influencing churn, and provide actionable
insights for retention strategies.
### Dataset Details
- *Source:* [Kaggle/Custom Dataset] (Provide the link if available)
- *File:* customer_churn.csv
- *Key Columns:*
- CustomerID - Unique identifier for customers
- Gender, Dependents, InternetService, InternetType
- Contract_1_year, Contract_2_year, Contract_2_year
- ChurnCategory_Dissatisfaction, ChurnCategory_Price, ChurnCategory_Others
- AvgMonthlyGBDownload, AvgMonthlyLongDistanceCharges
### Installation & Setup
1. Create a Virtual Environment
bash
python -m venv venv

2. Activate Virtual Environment
- On *Windows:*
bash
venv\Scripts�ctivate

- On *Mac/Linux:*
bash
source venv/bin/activate

3. Upgrade pip to the Latest Version
bash
pip install --upgrade pip

4. Install Required Packages
bash
pip install pandas numpy matplotlib seaborn jupyter

5. Run Jupyter Notebook
bash
jupyter notebook

### Folder Structure

CustomerChurnAnalysis/
??? data/
? ??? customer_churn.csv
??? notebooks/
? ??? churn_analysis.ipynb
??? README.md
??? requirements.txt

### Key Insights
- *Churn Reasons:* Most customers left due to dissatisfaction and pricing.
- *High Data Usage:* Customers with higher data usage had lower churn rates.
- *Contract Type:* Long-term contracts reduced churn significantly.
- *Churn Category:* ChurnCategory_Dissatisfaction had the highest count.
### Visualizations
- *Bar Charts:* For churn reasons and contract types.
- *Pie Charts:* For internet service distribution.
- *Correlation Heatmap:* Showcasing relationships between numerical features.
### Challenges Faced
- *Missing Data:* Handled using mean imputation.
- *Categorical Variables:* Converted using one-hot encoding.
- *Feature Scaling:* Applied to numerical data for better analysis.
### Conclusion
The analysis highlights the importance of pricing and customer satisfaction in reducing churn.
Offering incentives for long-term contracts and improving service quality can help retain customers
effectively.
