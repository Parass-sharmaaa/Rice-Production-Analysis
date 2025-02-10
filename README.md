# District-Wise Rice Production Analysis in India

## Project Overview
This project analyzes rice production data across various districts in India, focusing on identifying production trends, handling inconsistencies like temporal gaps, administrative boundary changes, and climate variability. The goal is to provide actionable insights to policymakers and farmers, enabling data-driven decision-making.

## Dataset
- **Source**: [Kaggle Dataset](https://kaggle.com)
- **Description**: The dataset contains district-wise data on rice production, harvested area, and yield for different years.

## Tools and Libraries
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Environment**: Google Colab, Jupyter Notebooks

## Project Scope and Expectations
This case study addresses three key challenges:
1. **Administrative or Boundary Changes Over Time**: Standardizing district names to account for changes and ensuring data consistency across years.
2. **Climate and Weather Variability**: Incorporating simulated climate data (e.g., rainfall) and analyzing its impact on rice production.
3. **Temporal Gaps or Inconsistent Time Ranges**: Filtering data to focus on a consistent time range from 1990 onward and identifying missing records.

## Project Steps
### 1. Data Ingestion
The dataset is loaded using Pandas and initial exploration is performed to understand its structure and content. Key steps include displaying data summaries, data types, and handling file paths in Google Colab.

### 2. Data Cleaning
- **Handling Missing Values**: Missing values were filled using the median for `RICE AREA` and the mean for `RICE PRODUCTION`.
- **Temporal Gaps**: Data from before 1990 was removed to ensure consistency.
- **Administrative Changes**: District names were standardized to account for changes over time.

### 3. Exploratory Data Analysis (EDA)
- Visualized production trends over time using line plots.
- Analyzed relationships between rainfall and rice production using scatter plots and line plots.
- Created bar plots for identifying top-producing states and districts.

### 4. Feature Engineering
- Added a new feature `Production per Area` to analyze the efficiency of production.
- Binned rainfall data and calculated the average production for each bin to reveal trends.

### 5. Predictive Modeling
- Built a linear regression model to predict future rice production based on `RICE AREA`.
- Evaluated the model using Mean Squared Error (MSE) and R² Score.

## Risks and Assumptions
- **Data Quality**: Assumes that the dataset is accurate and reliable.
- **Temporal Gaps**: Some districts have incomplete data for earlier years, which may impact trend analysis.
- **Administrative Changes**: Standardized district names might not capture all historical changes.
- **Climate Variability**: Simulated rainfall data was used for demonstration purposes. Accuracy depends on real climate data.

## Real-World Applicability
- **Performance**: The solution is scalable for larger datasets and optimized for efficient local execution.
- **Data Privacy**: No personal or sensitive data is used, ensuring compliance with data privacy standards.
- **Feasibility**: This approach can be extended to other crops and regions, making it practical for real-world agricultural analysis.

## Results and Insights
- **Top-Producing Districts**: Identified districts with the highest rice production.
- **Production Trends**: Found increasing/decreasing trends over the years.
- **Predictive Model**: Provided future estimates for rice production based on the linear regression model.

## Video Demonstration
1. **Functional Overview**: [YouTube Link](https://youtu.be/Tb1IqQMpGBk)
2. **Technical Walkthrough**: [YouTube Link](https://youtu.be/muJWFR2SHhM)

---
### Contact
For questions or suggestions, feel free to reach out!

