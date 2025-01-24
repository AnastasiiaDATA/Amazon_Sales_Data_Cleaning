# Marathon Running 2020 - Exploratory Data Analysis (EDA)

## Objective
The goal of this project is to analyze the Marathon Running 2020 dataset to uncover insights into runner demographics, performance trends, and factors influencing marathon outcomes. By performing exploratory data analysis (EDA), we aim to identify meaningful patterns and trends that can inform future studies or improve understanding of marathon performance.

---

## About the Data
The dataset contains detailed information about participants in a marathon event held in 2020. Key features include:

- **Runner Demographics**: Age, gender, and possibly location.
- **Performance Metrics**: Finish times, split times, and average pace.
- **Event Details**: Race categories (e.g., full marathon, half marathon) and potential external factors such as weather conditions.
- **Data Challenges**: Includes missing or incomplete data, requiring cleaning and preprocessing for accurate analysis.

This dataset offers opportunities to explore relationships between demographic factors and performance, as well as highlight trends and anomalies.

---

## Data Manipulations
The following manipulations were performed on the dataset:

1. **Data Cleaning**:
   - Addressed missing values via imputation or removal.
   - Standardized formats (e.g., time formats and categorical labels).
   - Removed outliers in numerical fields like finish times or age.

2. **Data Transformation**:
   - Engineered new features (e.g., pace per kilometer derived from finish times and distance).
   - Grouped data into categories for focused analysis (e.g., age groups, gender-based groups).
   - Normalized numerical fields where necessary.

3. **Data Exploration**:
   - Generated statistical summaries to understand data distributions.
   - Filtered subsets of data for targeted visualizations and analysis.

4. **Visualization Preparation**:
   - Aggregated data for comparative analyses (e.g., average finish times by gender).
   - Prepared data for various types of plots (e.g., histograms, scatter plots, box plots).

---

## Technologies Used
- **Jupyter Notebook**: For analysis and visualization.
- **Python Libraries**:
  - **Pandas**: Data manipulation and cleaning.
  - **NumPy**: Numerical computations.
  - **Matplotlib** and **Seaborn**: Data visualization.

---

## Insights
- Trends in runner performance based on age and gender.
- Analysis of average finish times across different race categories.
- Identification of outliers or anomalies in the dataset.
