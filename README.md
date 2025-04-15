# NBP-Players-Performance
Objective
This project aims to analyze and predict NBA player performance using machine learning models based on season-by-season statistics from the Seasons_Stats.csv dataset. The goal is to:

Learn data preprocessing techniques

Train regression models

Evaluate model performance using real NBA stats

📁 Dataset Used
File: Seasons_Stats.csv

Source: Contains NBA player stats by season (1980 onward filtered), including:

Basic stats: PTS, AST, TRB, STL, BLK, etc.

Advanced metrics: PER, WS, TS%, etc.

Metadata: Player, Year, Team, Position, etc.

🧰 Tools & Libraries
Python (Jupyter Notebook)

pandas, numpy

matplotlib, seaborn

scikit-learn

🔄 Workflow
Load & Inspect Dataset

Remove nulls and irrelevant columns

Filter modern era (post-1980 seasons)

Data Preprocessing

Handle missing values

Drop high-NaN columns

Select numerical features only

Feature scaling using StandardScaler

Model Building

Linear Regression

Random Forest Regressor

Ridge Regression

Decision Tree Regressor

Model Evaluation

Metrics: Mean Squared Error, R² Score

Visualizations: Actual vs Predicted plots

Results

Linear Regression (initial) showed signs of data leakage — corrected

Best performing model: To be filled based on final scores

📈 Sample Output
<img src="https://via.placeholder.com/600x300.png?text=Actual+vs+Predicted+Points" alt="Model Plot" />
✅ Next Steps
Add player height/weight from Players.csv for enhanced features

Try predicting other targets (e.g., PER, WS)

Use feature selection (e.g., SelectKBest or correlation matrix)

📂 Files in Repository
NBP Players Performance.ipynb: Jupyter Notebook with all code

Seasons_Stats.csv: Raw dataset

cleaned_season_stats.csv: Cleaned version (optional)

README.md: This file

