📊 Telecom Customer Churn Prediction & Retention Strategy
The Problem: A £137,000 Monthly Revenue Hole
Every business faces churn, but not every business understands its "Revenue Velocity." In this project, I analyzed a telecom dataset of 7,043 customers and discovered that while the company was gaining £19,420 from new acquisitions, it was losing £137,092 every month to churn.

This project provides a data-driven solution to identify high-risk "Whale" accounts before they leave.

🚀 The Solution: From Dashboard to Prediction
While traditional BI tools (like Power BI) are excellent for reporting the past, I used Python and Machine Learning to predict the future.

1. Exploratory Data Analysis (EDA)
The "Danger Zone": Identified that most churn occurs within the first 0–6 months of a customer’s tenure.

Toxic Drivers: Isolated Fiber Optic internet and Month-to-Month contracts as the primary statistical drivers of attrition.

Visualization: Built correlation heatmaps and distribution plots to identify "at-risk" personas.

2. Machine Learning Pipeline
Preprocessing: Handled missing values and used One-Hot Encoding to transform categorical strings (Gender, Service Type, etc.) into mathematical features.

Model: Developed a Random Forest Classifier to analyze behavioral patterns.

Metric: Focused on Churn Probability (%), allowing for a tiered risk intervention strategy rather than a simple binary "Yes/No."

3. Business Impact (The Watchlist)
The final output is an AI-Powered Retention Watchlist. This tool categorizes active customers into:

Critical Risk (80%+): High-value accounts requiring immediate human intervention.

Moderate Risk (50-79%): Accounts flagged for automated loyalty marketing and service audits.

🛠️ Tech Stack
Language: Python 3.x

Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn

Deployment: Model persistence achieved via joblib for future batch processing.

📈 Key Findings & Recommendations
Contract Migration: Transitioning "Month-to-Month" users to long-term plans could reduce churn risk by up to 4x.

Premium Service Audit: Investigate Fiber Optic hardware/pricing, as this premium tier is currently the most unstable revenue source.

Onboarding Focus: Implement high-touch customer success sequences during the first 90 days to bridge the initial tenure gap.

📂 Project Structure
Churn analysis and Prediction.ipynb: The full analytical and modeling pipeline.

AI_Powered_Retention_Watchlist.csv: The actionable list for the Sales/Retention team.
