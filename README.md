# 🛢️ Oily Giant – Optimizing Oil Well Placement with Linear Regression and Risk Analysis
## 🔍 Project Functionality
This project supports decision-making for opening 200 new oil wells in one of three candidate regions. The goal is to maximize profits and minimize financial risks by analyzing geological data and predicting reserve volumes using a linear regression model. The project includes model training, profit simulations, and statistical risk assessments to recommend the most promising region for investment within a fixed budget of $100 million.

## 🛠️ Technologies and Methods
Python with Pandas, NumPy, Scikit-learn, Bootstrapping

Linear Regression models trained separately for each region

Custom pipeline of reusable functions:

Data preparation (prepare_data)

Model training and validation (train_and_validate)

Result analysis and prediction quality (analyze_results)

Evaluation metric: RMSE (Root Mean Squared Error)

**Profit simulation:**

Select top 200 predicted wells

Estimate profit using reserve volume and per-barrel revenue

Statistical risk analysis with Bootstrapping:

1,000 simulations per region

95% confidence intervals for profit

Risk of loss estimation

## 📈 Key Findings and Conclusion
**Model performance by region:**

Region 0: Predicted average = 92.64, RMSE = 37.69

Region 1: Predicted average = 68.48, RMSE = 0.89 (very stable)

Region 2: Predicted average = 95.24, RMSE = 40.19

**Simulated average profit (top 200 wells):**

Region 0: $39.3M, CI: [$38.1M, $40.5M], Risk: 0%

Region 1: $24.8M, CI: [$24.7M, $24.8M], Risk: 0%

Region 2: $33.2M, CI: [$32.3M, $34.1M], Risk: 0%

Region 1 offers the most predictable outcome, but lower returns.

Region 0 provides the highest average profit and no risk of loss, with a reasonably tight confidence interval, making it the optimal choice.

✅ Recommendation: Invest in Region 0. It offers the best balance between high expected profit and low uncertainty, fulfilling both financial and operational goals.
