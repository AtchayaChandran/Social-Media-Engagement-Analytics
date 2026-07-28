# 📊 Social Media Engagement Analytics using Python

> A comprehensive data analysis project that explores social media engagement patterns using Python. This project demonstrates the complete data analytics workflow, including data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization to derive meaningful business insights.

---

# 📌 Table of Contents

- Project Overview
- Problem Statement
- Objectives
- Dataset Information
- Technologies Used
- Python Libraries
- Project Workflow
- Data Cleaning
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Business Insights
- Project Structure
- Installation
- How to Run
- Future Improvements
- Learning Outcomes
- Screenshots
- Author

---

# 📖 Project Overview

Social media platforms generate massive amounts of user interaction data every day. Understanding how users engage with different types of content helps businesses, marketers, and influencers improve their content strategy.

This project performs an end-to-end analysis of a Social Media Engagement dataset using Python. The analysis focuses on understanding user behavior, engagement trends, post performance, and country-wise engagement using descriptive statistics and visual analytics.

---

# ❓ Problem Statement

Organizations often struggle to understand:

- Which post type receives higher engagement?
- Which countries generate higher impressions?
- Does user sentiment affect engagement?
- Is there a relationship between watch time and engagement score?
- What patterns can be observed from user interactions?

This project answers these questions using data analysis techniques.

---

# 🎯 Objectives

The main objectives of this project are:

- Import and inspect the dataset.
- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Convert date columns into proper datetime format.
- Explore the dataset using descriptive statistics.
- Analyze engagement metrics.
- Compare engagement across categories.
- Visualize important trends.
- Perform correlation analysis.
- Generate meaningful business insights.

---

# 📂 Dataset Information

| Attribute | Details |
|-----------|----------|
| Dataset Name | Social Media Engagement Dataset |
| Records | 5,000 |
| File Format | CSV |
| Analysis Tool | Python |

The dataset contains user engagement information including:

- User Details
- Post Information
- Likes
- Comments
- Shares
- Watch Time
- Impressions
- Engagement Score
- Sentiment
- Country
- Device Type

---

# 🛠️ Technologies Used

- Python
- Google Colab
- Jupyter Notebook

---

# 📚 Python Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly

---

# 🔄 Project Workflow

```
Data Collection
        │
        ▼
Data Import
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Statistical Analysis
        │
        ▼
Data Visualization
        │
        ▼
Business Insights
```

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Imported CSV dataset
- Checked dataset dimensions
- Displayed column names
- Inspected data types
- Checked missing values
- Removed duplicate records
- Converted date column into datetime format
- Verified cleaned dataset

---

# 📊 Exploratory Data Analysis (EDA)

The following analysis was performed:

### Dataset Inspection

- First 5 rows
- Last 5 rows
- Dataset shape
- Column names

### Descriptive Statistics

- Count
- Mean
- Standard Deviation
- Minimum
- Maximum
- Quartiles

### Group-wise Analysis

Average Likes by Post Type

Average Impression Count by Country

Average Engagement Score by

- Post Type
- Country
- Sentiment

---

# 📈 Statistical Analysis

The following statistical measures were calculated:

- Mean
- Median
- Standard Deviation
- Correlation Matrix

Correlation analysis was performed to identify relationships between numerical variables.

---

# 📉 Data Visualization

The project includes multiple visualizations:

✅ Bar Chart

- Average Likes by Post Type

✅ Histogram

- Engagement Score Distribution

✅ Box Plot

- Likes Distribution

✅ Scatter Plot

- Watch Time vs Engagement Score

✅ Correlation Heatmap

- Relationship between numerical variables

✅ Interactive Plotly Chart

- Dynamic exploration of engagement metrics

---

# 💡 Business Insights

From the analysis, the following insights were observed:

- Different post types generate varying levels of engagement.
- Engagement score differs across countries.
- User sentiment has an influence on engagement.
- Watch time and engagement score show only a weak correlation.
- Visualizations provide better understanding of user interaction patterns.

---

# 📁 Project Structure

```
Social-Media-Engagement-Analytics/
│
├── Social_Media_Engagement_Analytics.ipynb
├── social_media_engagement_5000.csv
├── README.md
└── images/
      ├── bar_chart.png
      ├── histogram.png
      ├── boxplot.png
      ├── scatterplot.png
      ├── heatmap.png
      └── plotly_chart.png
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Social-Media-Engagement-Analytics.git
```

Move into the project directory

```bash
cd Social-Media-Engagement-Analytics
```

Install dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly
```

---

# ▶️ How to Run

1. Download the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required libraries.
4. Upload the dataset.
5. Run all notebook cells sequentially.

---

# 🚀 Future Improvements

Possible enhancements include:

- Predict engagement score using Machine Learning
- Build an interactive Power BI Dashboard
- Create a Streamlit web application
- Perform Time Series Analysis
- Deploy the project online

---

# 🎓 Learning Outcomes

Through this project, the following concepts were applied:

- Data Import
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Correlation Analysis
- Business Insight Generation
- Python Programming
- Pandas Operations
- Plotly Visualizations

---

# 📸 Screenshots

Add screenshots of:

- Dataset Preview
- Bar Chart
  <img width="944" height="640" alt="Screenshot 2026-07-28 221711" src="https://github.com/user-attachments/assets/2bfe2d32-8c7f-49f0-be09-63a66b7220e3" />

- Histogram
  <img width="926" height="620" alt="Screenshot 2026-07-28 221921" src="https://github.com/user-attachments/assets/6458623c-4ccb-4355-80d4-dcdaaa98fd1d" />

- Box Plot
  <img width="851" height="629" alt="Screenshot 2026-07-28 222019" src="https://github.com/user-attachments/assets/720852a0-269e-434e-82d5-f0763d478e95" />

- Scatter Plot
  <img width="940" height="615" alt="Screenshot 2026-07-28 222108" src="https://github.com/user-attachments/assets/54e74553-8ed1-4041-929b-348a449e9ebc" />

- Heatmap
  <img width="1212" height="1036" alt="Screenshot 2026-07-28 222153" src="https://github.com/user-attachments/assets/7db2761a-c159-4fad-9810-58edaf022d72" />

- Plotly Visualization
   <img width="1879" height="662" alt="Screenshot 2026-07-28 222751" src="https://github.com/user-attachments/assets/70ffe95e-36cc-40fb-a500-e16474f62283" />


---

# 👩‍💻 Author

**Atchaya Chandran**

Python for Data Analysis – Module End Project

---

# ⭐ Acknowledgement

This project was developed as part of the **Python for Data Analysis Module-End Assignment**, demonstrating the complete workflow of data preprocessing, exploratory data analysis, statistical analysis, and visualization using Python.
