# Zeotap-Task-Submission

Here’s a corrected version of the `README.md` where I’ve outlined exactly what you would have used for each task, based on the tools, libraries, and methods you mentioned:

---

# Zeotap Internship: Data Science Assignment

This repository contains my solution for the Zeotap Internship Data Science assignment. The assignment involves working with an eCommerce transactions dataset to perform Exploratory Data Analysis (EDA), build a Lookalike Model, and implement Customer Segmentation using clustering techniques.

## Table of Contents
1. [Task 1: Exploratory Data Analysis (EDA) and Business Insights](#task-1)
2. [Task 2: Lookalike Model](#task-2)
3. [Task 3: Customer Segmentation / Clustering](#task-3)
4. [File Naming Convention](#file-naming-convention)
5. [Submission Instructions](#submission-instructions)

---

## Task 1: Exploratory Data Analysis (EDA) and Business Insights

### Tools Used:
- **Pandas**: For loading, cleaning, and manipulating the data.
- **Matplotlib** and **Seaborn**: For creating visualizations such as histograms, bar plots, and scatter plots.
- **NumPy**: For handling numerical operations, including data imputation and transformations.
- **Jupyter Notebook**: To run all the code interactively.

### What I Did:
For Task 1, I performed an exploratory data analysis (EDA) on the provided dataset. I explored key relationships between customer demographics, product information, and transaction history. The analysis helped uncover patterns in customer behavior and identify product performance trends.

### Key Insights:
- Examined customer distribution across different regions.
- Analyzed transaction frequency and total sales value.
- Identified product categories with the highest sales volume.
- Determined seasonal trends in customer purchases.

### Deliverables:
- **Code**: Jupyter Notebook (`FirstName_LastName_EDA.ipynb`) containing EDA code.
- **Report**: PDF report (`FirstName_LastName_EDA.pdf`) summarizing business insights.

---

## Task 2: Lookalike Model

### Tools Used:
- **Scikit-learn**: For computing similarity scores using cosine similarity.
- **Pandas**: For data manipulation and merging customer and transaction datasets.
- **Jupyter Notebook**: For implementing the Lookalike model and running tests.

### What I Did:
For Task 2, I developed a Lookalike Model that identifies similar customers based on demographic and transactional data. I calculated similarity scores using **cosine similarity** to recommend the top 3 customers most similar to each input customer.

### Approach:
- Cleaned and preprocessed customer and transaction data.
- Applied **cosine similarity** to calculate how similar the customers were based on their demographic and transactional characteristics.
- Generated recommendations for the first 20 customers in the dataset.

### Deliverables:
- **Code**: Jupyter Notebook (`FirstName_LastName_Lookalike.ipynb`) with model implementation.
- **Output**: CSV file (`FirstName_LastName_Lookalike.csv`) containing similarity scores and recommended customers for the first 20 customers.

---

## Task 3: Customer Segmentation / Clustering

### Tools Used:
- **Scikit-learn**: For K-Means clustering and calculating the Davies-Bouldin (DB) Index.
- **Matplotlib** and **Seaborn**: For visualizing the customer segments and clusters.
- **Pandas**: For data manipulation and preparing the dataset for clustering.
- **Jupyter Notebook**: For running the clustering code and visualizing results.

### What I Did:
For Task 3, I applied clustering techniques to segment customers based on their profile and transaction history. I used the **K-Means clustering** algorithm to form customer groups and evaluated the clustering results using the **Davies-Bouldin Index**.

### Approach:
- Preprocessed customer and transaction data to handle missing values and scale numerical features.
- Applied **K-Means clustering** to form 4 clusters (based on the DB Index evaluation).
- Evaluated the clustering quality using **Davies-Bouldin (DB) Index**.
- Visualized the clusters using scatter plots to represent customer segments.

### Deliverables:
- **Code**: Jupyter Notebook (`FirstName_LastName_Clustering.ipynb`) containing the clustering code.
- **Report**: PDF report (`FirstName_LastName_Clustering.pdf`) detailing clustering results, number of clusters, and DB Index value.

---

## File Naming Convention

All files should be named according to the following format:
- **EDA**: `FirstName_LastName_EDA.ipynb`, `FirstName_LastName_EDA.pdf`
- **Lookalike Model**: `FirstName_LastName_Lookalike.ipynb`, `FirstName_LastName_Lookalike.csv`
- **Clustering**: `FirstName_LastName_Clustering.ipynb`, `FirstName_LastName_Clustering.pdf`

---

## Submission Instructions

1. **GitHub Repository**:
   - Upload all the necessary files (code and reports) to a public GitHub repository.
   - Ensure the file names follow the naming convention mentioned above.

2. **Evaluation**:
   - The submission will be evaluated based on the following criteria:
     - **Exploratory Data Analysis** (25%)
     - **Business Insights** (15%)
     - **Lookalike Model** (30%)
     - **Customer Segmentation** (30%)

---
