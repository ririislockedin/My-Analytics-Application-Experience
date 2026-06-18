# My-Analytics-Application-Experience

The primary goal across the notebooks is to provide a comprehensive training and practical application of data analysis and data science techniques. The main focus is on loading, organizing, exploring, and analyzing datasets using Python libraries like pandas and a custom library, qdesc. Topics range from basic data handling and descriptive statistics to advanced correlation and strategic data-driven insights for decision-making.

The most frequently used and fundamental Python packages in the notebooks are:

  pandas (pd): Essential for loading data from various formats (like Excel and CSV) and performing data manipulation and organization in DataFrame structures.
  
  qdesc (qd): A custom or specialized library used for quick descriptive statistics and exploratory data analysis (EDA), including functions for frequency        distributions and normality checks.
  
  Other common packages include numpy, scipy.stats, seaborn, and matplotlib.pyplot for numerical operations, statistical tests, and data visualization.

The notebooks demonstrate several key data science tasks, falling into three main areas:

Data Loading and Organization: Using pd.read_excel and pd.read_csv to load data, and employing techniques to identify and manage missing values.

  Exploratory Data Analysis (EDA) and Descriptives: Generating frequency distributions (qd.freqdist_a), checking for normality (qd.normcheck_dashboard), and calculating basic statistics.
  
  Inferential Analysis: Exploring associations between numerical variables by checking assumptions (normality, linearity) and applying appropriate correlation techniques (Pearson, Spearman, Kendall’s Tau-b).

4. Final Conclusion/Recommendations of the "Board Level Strategic Insight Request"
The final conclusion of the "Board Level Strategic Insight Request" notebook focuses on the statistically significant drivers of loan amount. It identifies CreditScore, EmploymentYears, and Income (positive influence), along with DebtToIncome (negative influence), as primary drivers. The recommendation is to move beyond simple analysis and build a validated multivariable decision model combining these features with other operational variables. It further suggests piloting controlled automation with human-in-the-loop review and monitoring.
