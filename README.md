**Sea Level Analysis and Prediction**

 **Overview**
This project analyzes global sea level data over time using a provided dataset (`sealevel.csv`). The analysis includes identifying trends, calculating yearly changes, and predicting future sea levels using a machine learning model. The insights from this project aim to highlight the potential impacts of rising sea levels on ecosystems, human settlements, and economies.

---

**Data Description**
The dataset (`sealevel.csv`) contains the following key columns:
- **Year**: The year of observation.
- **Global_Mean_Sea_Level**: Sea level measurements in millimeters, adjusted for GIA (Glacial Isostatic Adjustment).

---

 **Key Analysis and Findings**

 **Trend Analysis**
- The global mean sea level is observed to be **rising steadily**, with potential signs of **acceleration** in recent years.
- A line plot was used to visualize the trend over time, showing a consistent increase in sea levels.

 **Yearly Change**
- Year-over-year changes in sea levels were calculated to identify significant deviations.
- Notable years with significant changes include:
  - Years where the change was **higher than average**, indicating possible environmental or climatic disruptions.
  - Years with **minimal or negative changes**, providing insights into anomalies.

 **Prediction**
- Using a **Linear Regression Model**, future sea levels were predicted for the years 2024 to 2050.
- The projection suggests a **continued rise in sea levels**, which may have significant impacts, including:
  - Increased risk of flooding in low-lying areas.
  - Threats to coastal ecosystems and infrastructure.
  - Potential displacement of human populations in vulnerable regions.

---

 **Project Files**
- **`sealevel.csv`**: The input dataset containing historical sea level data.
- **Analysis Notebook**: A Python notebook containing all the code used for analysis and visualization.
- **Generated Plots**: Visualizations of trends, yearly changes, and predictions.

---

 **Technologies Used**
- **Python**: Primary programming language.
- **Libraries**:
  - `pandas` for data manipulation.
  - `matplotlib` and `seaborn` for visualization.
  - `scikit-learn` for machine learning (Linear Regression Model).

---

## **How to Run**
.  Clone the repository:
   ```bash
   git clone https://github.com/MissSilola/GloabalSeaLevels.git
