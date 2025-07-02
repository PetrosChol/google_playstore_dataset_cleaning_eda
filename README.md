### Google Play Store App Analysis

This project presents a comprehensive analysis of the Google Play Store dataset to uncover key factors that contribute to app success. The analysis follows the entire data science pipeline, from deep data cleaning and preprocessing to exploratory data analysis (EDA) and insight generation.

A key challenge in this dataset was a corrupted data row that required careful investigation and removal. This discovery informed a robust cleaning process and a statistically-backed approach to imputing missing values, which is detailed in the notebook.

**Key Features & Skills Demonstrated:**

*   **Data Cleaning & Preprocessing:** Handled corrupted data, duplicate entries, and incorrect data types.
*   **Statistical Analysis & Imputation:** Used the Kruskal-Wallis H-test to justify a category-based median imputation for missing `Rating` and `Size` values—a more rigorous approach than simple global imputation.
*   **Exploratory Data Analysis (EDA):** Investigated relationships between app features like category, installs, and reviews using correlation matrices and univariate/bivariate analysis.
*   **Data Visualization:** Created clear and insightful visualizations using `Seaborn` and `Matplotlib` to communicate findings effectively.
*   **Problem Solving:** Demonstrated a methodical approach to identifying and resolving data integrity issues.

**Technologies Used:**
*   Python
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn
*   SciPy
*   Scikit-posthocs
