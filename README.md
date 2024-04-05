# Assignment 4 Overview:

### Correlation and the relationship between different variables

In this assignment, I utilized Apache Spark and Databricks Community Edition to perform correlation analysis on the Iris dataset.
The primary objectives were to calculate correlations between different variables using both DataFrame API and RDD, and then visualize
the correlation matrix as a heatmap.

## 1. Data Access:

To facilitate ease of access and processing, I downloaded the Iris dataset from the
provided URL: https://raw.githubusercontent.com/selva86/datasets/master/Iris.csv and
stored it in the local file store. This dataset contains information about the Sepal and
Petal dimensions of three different species of Iris flowers: Setosa, Versicolor, and Virginica.

## 2. Calculate Correlation Using DataFrame API:

Using the DataFrame API in Apache Spark, I calculated the correlation between various attributes
of the Iris dataset. Specifically, I employed the corr() function to compute the correlation
coefficients between different pairs of numerical variables. This allowed me to determine the
strength and direction of the linear relationships between these variables.

## 3. Calculate Correlation Using RDD:

In addition to the DataFrame API, I also utilized Resilient Distributed Datasets (RDDs) in Spark to calculate
the correlation. By converting the DataFrame to an RDD of Vectors and applying the Statistics.corr() function,
I obtained the correlation matrix, which provided similar insights into the relationships between variables.

## 4. Correlation Heatmap Using Correlation Matrix:

To visually represent the correlation matrix, I created a correlation heatmap. This heatmap provided an intuitive
visualization of the correlation coefficients between different pairs of variables in the Iris dataset. The heatmap
helped in identifying patterns, strengths, and directions of correlations, facilitating a deeper understanding of
the dataset's characteristics.

Throughout the assignment, I documented each step, including code implementation, results, and interpretations.
The screenshots from the notebook illustrate the process and outcomes of the correlation analysis, demonstrating
proficiency in utilizing Spark for data analysis tasks.
