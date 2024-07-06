# IPL 2024 Exploratory Data Analysis (EDA)

## Project Overview

This project involves an exploratory data analysis (EDA) of the IPL 2024 dataset. The objective is to dive deep into the data to understand team performances, player statistics, match outcomes, and more. The analysis aims to uncover valuable insights and trends within the dataset, enhancing skills in data cleaning, visualization, and statistical analysis using Python.

## Dataset

The dataset used for this analysis includes:
- `matches.csv`: Contains details about the matches played.
- `deliveries.csv`: Contains ball-by-ball data of the matches.

## Tools and Techniques Used

- **Data Loading and Cleaning:**
  - pandas for data manipulation.
  - Handling missing values and removing duplicates.

- **Descriptive Statistics:**
  - Calculating mean, median, mode, and standard deviation for numerical data.
  - Summarizing counts and percentages for categorical data.

- **Data Visualization:**
  - seaborn and matplotlib for creating heatmaps, bar plots, scatter plots, and other visualizations.

- **Correlation Analysis:**
  - Generating and visualizing a correlation matrix to identify relationships between variables.

- **Cluster Analysis:**
  - Applying k-means clustering for analyzing team performances.

## Key Insights

### Team Performance

- Teams like Mumbai Indians showed consistent performance.![Team Rankings Over Time](https://github.com/Aasthachourasiya0/EDA_IPL-2024_Analysis-/assets/162965188/1779e19a-3d68-449c-afba-a617f5a1dda3)

- Dominant teams exhibited significant winning streaks.![Head-to-Head Performance](https://github.com/Aasthachourasiya0/EDA_IPL-2024_Analysis-/assets/162965188/a84c0d2b-8219-43af-af2d-5068067a076c)


### Player Performance

- Identified top performers such as AB de Villiers.![Top 10 Players of the Match](https://github.com/Aasthachourasiya0/EDA_IPL-2024_Analysis-/assets/162965188/3eb8f8e9-11fc-43ed-af7a-a1414c027f0e)

- All-rounders had a significant impact on match outcomes.![Impact of Player Roles on Match Outcomes](https://github.com/Aasthachourasiya0/EDA_IPL-2024_Analysis-/assets/162965188/7442e0d7-c5a2-47f7-863e-f998b4e54aba)


### Match Outcome

- Toss decisions played a crucial role in match outcomes.
-![Venues for High-Scoring Matches](https://github.com/Aasthachourasiya0/EDA_IPL-2024_Analysis-/assets/162965188/38152075-ffc0-4907-9d45-06afbe875b2e)

- High-scoring matches had distinct characteristics.
![Toss Choice](https://github.com/Aasthachourasiya0/EDA_IPL-2024_Analysis-/assets/162965188/8e1c7cd7-db24-498e-aeb2-caffd41b70d4)

- Correlation Analysis
- ![Correlation Matrix of Matches Dataset](https://github.com/Aasthachourasiya0/EDA_IPL-2024_Analysis-/assets/162965188/89e24ed3-80c8-4a90-b5c3-bf45cac9d5e2)

## Additional Insights

- Player injuries adversely affected team performance.
- New players positively impacted team dynamics.
- Potential correlations between fan engagement and team performance were identified but require further analysis.

## Suggested Areas for Further Investigation

- **Predictive Modeling:** Forecasting match outcomes using machine learning techniques.
- **Venue Impact:** Analyzing how different venues affect team performance.
- **Fan Engagement Analysis:** Investigating the correlation between fan engagement metrics and team performance.

## Conclusion

This comprehensive EDA has highlighted the importance of thorough data cleaning, visualization, and statistical analysis in extracting meaningful insights. The dataset offers potential for further analysis, including predictive modeling and strategic decision-making.

## References and Sources
- Dataset Source: [Kaggle - IPL Complete Dataset (2008-2020)](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020/data)

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- Python 3.6+
- Jupyter Notebook
- Required libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/IPL-2024-EDA.git
