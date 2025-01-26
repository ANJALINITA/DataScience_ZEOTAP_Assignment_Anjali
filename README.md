# Data-Science-Intern-Assignment-Zeotap
eCommerce Transactions Dataset - Data Science Assignment
Overview
This project involves performing exploratory data analysis (EDA), building a lookalike model, and conducting customer segmentation using a provided eCommerce transactions dataset. The dataset consists of three files:

Customers.csv: Customer details including ID, name, region, and signup date.
Products.csv: Product information including ID, name, category, and price.
Transactions.csv: Transaction records including customer ID, product ID, date, quantity, total value, and product price.
The assignment is split into three tasks:

Task 1: Exploratory Data Analysis (EDA) and Business Insights
Perform exploratory data analysis (EDA) on the dataset to identify key patterns and trends.
Derive at least 5 actionable business insights based on the EDA results. Insights should be concise (maximum 100 words per insight).
Deliverables:
Jupyter Notebook/Python script containing the EDA code.
PDF report with business insights (maximum 500 words).
Task 2: Lookalike Model
Build a Lookalike Model that recommends 3 similar customers based on a user's profile and transaction history.
Use both customer and product information.
Assign a similarity score to each recommended customer.
Deliverables:
List of top 3 lookalikes with similarity scores for the first 20 customers (CustomerID: C0001 - C0020).
A CSV file Lookalike.csv with the format: Map<cust_id, List<cust_id, score>>.
Jupyter Notebook/Python script explaining the model development.
Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques with both profile and transaction data.
Choose any clustering algorithm and select the number of clusters (between 2 and 10).
Calculate clustering metrics, including the DB Index.
Visualize the clusters using appropriate plots.
Deliverables:
Report on clustering results including:
Number of clusters formed.
DB Index value.
Other relevant clustering metrics.
Jupyter Notebook/Python script containing the clustering code.
Evaluation Criteria:
Task 1: EDA thoroughness and business insight quality.
Task 2: Model accuracy, recommendation quality, and logic.
Task 3: Clustering logic, evaluation metrics, and visualizations.
Requirements:
Python 3.x
Pandas
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
