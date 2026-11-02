# MSCS 634 – Lab 1
## Data Visualization, Data Preprocessing, and Statistical Analysis Using Python

### Project Overview
This lab demonstrates data visualization, data preprocessing, and statistical analysis using Python in Jupyter Notebook. The project uses the Titanic passenger dataset to explore passenger demographics, identify data quality issues, clean the dataset, and investigate patterns associated with passenger survival.

### Dataset
**Dataset:** Titanic Passenger Dataset

**Source:** [Titanic Dataset – GitHub](https://github.com/datasciencedojo/datasets/blob/master/titanic.csv)

The dataset contains 891 passenger records and 12 columns, including passenger class, sex, age, fare, embarkation port, and survival status.

### Technologies Used
- Python 3
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

### Lab Objectives
1. Load and explore a real-world dataset.
2. Perform exploratory data analysis (EDA).
3. Create meaningful data visualizations.
4. Identify and handle missing values.
5. Detect and evaluate outliers.
6. Apply data transformations and feature scaling.
7. Perform descriptive statistical analysis.
8. Interpret findings and communicate results.

### Data Visualization
The project explores the Titanic dataset through visualizations such as:
- Passenger survival distribution
- Survival patterns by gender and passenger class
- Age and fare distributions
- Correlation heatmaps

These visualizations help identify patterns, relationships, and differences across passenger groups.

### Data Preprocessing
The preprocessing workflow includes:

**Missing values:** Identifying incomplete records and applying suitable imputation techniques.

**Outliers:** Examining unusual values using statistical measures and visualizations.

**Categorical variables:** Converting categorical information into a form suitable for analysis.

**Feature scaling:** Standardizing numerical features where appropriate.

**Data validation:** Checking the processed dataset for consistency and remaining missing values.

### Statistical Analysis
The notebook performs descriptive statistical analysis using:
- Mean and median
- Standard deviation
- Minimum and maximum
- Quartiles and interquartile range
- Correlation analysis
- Group-based survival comparisons

### Key Findings
- Passenger survival varied across gender and ticket class.
- Passenger age and ticket fare showed different distribution patterns.
- The dataset contained missing values requiring preprocessing.
- Outlier analysis revealed unusually high ticket fares.
- Standardization transformed numerical features onto a comparable scale.

These findings are exploratory associations and do not establish causation.

### How to Run the Project
1. Clone the repository.
2. Open the project folder in Jupyter Notebook or JupyterLab.
3. Install the required Python libraries.
4. Open `MSCS_634_Lab_1.ipynb`.
5. Run the notebook cells sequentially.
6. Review the visualizations, statistical results, and interpretations.

**Install dependencies:**

```bash
pip install numpy pandas matplotlib seaborn scikit-learn notebook
```

**Launch Jupyter Notebook:**

```bash
jupyter notebook
```

### Project Files
- `MSCS_634_Lab_1.ipynb` – Main notebook containing Python code and analysis.
- `screenshots/` – Evidence of executed notebook steps and visualizations.
- `README.md` – Project documentation.
- `titanic.csv` – Original dataset, if stored locally.
- `requirements.txt` – Python dependency list, if included.

### Conclusion
This lab demonstrates a complete introductory data analysis workflow, from exploring raw data to preprocessing, visualizing, and interpreting results. It highlights the importance of data quality and clear visual communication in statistical analysis.

### Course Information
**Course:** MSCS 634

**Assignment:** Lab 1 – Data Visualization, Data Preprocessing, and Statistical Analysis Using Python

**Environment:** Python / Jupyter Notebook
