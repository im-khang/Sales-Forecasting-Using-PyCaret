# AutoML for Sales Forecasting: A Comparative Analysis for Retail Supply Chains

## Introduction (About Me)
I am **Nguyen Duy Khang**, a final-year Industrial Management student at Ho Chi Minh University of Technology (HCMUT), specializing in **Operations and Supply Chain Management**. With internship experience in **demand forecasting, KPI reporting, and Power BI dashboard design**, I am building a career as a **Supply Chain Analyst**—using data-driven methods to improve forecasting, planning, and logistics performance.

## Core Business Problem (Problem)
Accurate **demand forecasting** is critical for retail supply chains to optimize inventory, reduce costs, and improve customer service. However, selecting the best forecasting model is often a **complex and time-consuming challenge**. Businesses risk either overstocking (leading to high holding costs) or stockouts (leading to lost sales) if the wrong model is applied.

## My Approach & Methodology (Approach)
To address this challenge, I applied **PyCaret’s AutoML framework** to a real-world **retail sales dataset (2010–2018, 8+ years)**:

- **Data Preparation**: Cleaned and structured historical retail sales data for analysis.  
- **Model Comparison**: Used PyCaret to automate training and evaluation of multiple forecasting models, including:  
  - Traditional statistical models: ARIMA, Exponential Smoothing, Polynomial Trend Forecaster  
  - Machine learning models: Random Forest, Gradient Boosting, and other tree-based regressors  
- **Evaluation Metrics**: Forecast accuracy was compared using **MASE, RMSE, and MAE**.  
- **Systematic Selection**: Identified the most suitable forecasting approach based on quantitative results.

## Key Findings & Business Insights (Insight)
The **Polynomial Trend Forecaster**, a traditional statistical model, outperformed more complex machine learning models on this dataset.  

**Business Implication:**  
This finding highlights a critical insight for retail operations: **cutting-edge ML is not always the best solution**. For datasets with strong seasonal or trend components, **well-tuned statistical models can deliver higher accuracy and easier interpretability**. This means:  
- More reliable sales forecasts  
- Better alignment of procurement and production  
- Lower risk of costly inventory imbalances  

## Business Impact (Impact)
This project demonstrates how **automated model selection** enables supply chain leaders to make **faster, evidence-based forecasting decisions**. By identifying the most accurate model:  
- Stockouts and overstocking risks are reduced  
- Working capital efficiency is improved  
- Profit margins and customer satisfaction are protected  

## Technical Skills Showcase
- **Data Analysis**: Python, Pandas, Matplotlib  
- **Machine Learning**: PyCaret, AutoML, Time Series Analysis, Model Comparison  
- **Supply Chain Analytics**: Demand Forecasting, KPI Measurement (MAE, RMSE, MASE)  
- **Visualization & Reporting**: Power BI, Dashboard Design  

## How to Run
```bash
# Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# Install dependencies
pip install -r requirements.txt
