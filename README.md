## Football Player Shooting Data Exploration

This project explores shooting performance data from the 2023–2024 Premier League season. The aim is to demonstrate a complete data exploration workflow, from data inspection and cleaning through feature engineering and exploratory data analysis.

### Dataset
The dataset contains player-level shooting statistics, including goals, shots, shots on target, expected goals, and minutes played. The raw data required cleaning due to missing values, inconsistent date formats, and duplicated records.

The cleaned dataset is available in the `data` folder.

### Analysis Notebook
The full analysis is contained in the Jupyter notebook below:
- `notebooks/football_shooting_data_exploration.ipynb`

### Methods
• Initial data inspection and quality checks  
• Handling missing values and duplicates  
• Standardising date formats  
• Feature engineering of football-specific metrics such as:
  • Goals per 90 minutes
  • Shot accuracy
  • Goal conversion rate  
• Exploratory data analysis using summary statistics and visualisations  
• Correlation analysis of shooting metrics  

### Key Insights
• Most players have very low goals per 90, with a small number of high-performing outliers  
• Shot accuracy and goal conversion rate show a moderate positive relationship  
• Scoring output varies significantly by position and playing time  

### Tools
Python, pandas, numpy, matplotlib, seaborn
