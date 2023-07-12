# RFM-Analysis
The goal of this project was to perform RFM (Recency, Frequency, Monetary) Analysis using Python. RFM Analysis is a customer segmentation technique used to understand and categorize customers based on their buying behavior. The project aimed to calculate the RFM values for each customer in a dataset and analyze their patterns and behaviors.

The project was developed by implementing several steps:

1. Importing necessary Python libraries: The project started by importing pandas, plotly, and other required libraries for data manipulation and visualization.

2. Loading and preparing the dataset: A dataset containing customer IDs, purchase dates, and transaction amounts was loaded into a pandas DataFrame. The purchase date was converted to a datetime format, and recency, frequency, and monetary values were calculated for each customer.

3. Calculating RFM scores: RFM scores were calculated by assigning scoring criteria to the recency, frequency, and monetary values. The scores were then added to the dataset.

4. RFM value segmentation: The dataset was segmented into different RFM value segments (e.g., low-value, mid-value, high-value) based on the RFM scores. The segmentation was done using the pd.qcut() function.

5. RFM customer segmentation: Broader RFM customer segments (e.g., Champions, Potential Loyalists, Can't Lose) were created based on the RFM scores. Customers were assigned to specific segments using conditional statements.

6. Visualizations: Various visualizations, such as bar charts, treemaps, and heatmaps, were created to analyze and present the RFM segments and their distributions. The visualizations provided insights into the customer segments and their RFM values.

Some important features of the project are:

- RFM Calculation: The project calculated the recency, frequency, and monetary values for each customer based on their purchase behavior.

- RFM Scoring: Scoring criteria were defined for the RFM values to assign scores representing the customer's engagement, loyalty, and value.

- RFM Segmentation: The project segmented customers into RFM value segments and RFM customer segments, allowing for a deeper understanding of customer behavior and characteristics.

- Visualizations: The project utilized various visualizations, including bar charts, treemaps, and heatmaps, to present the RFM segments and their distributions, aiding in the interpretation and analysis of the results.

Overall, this project provides a comprehensive implementation of RFM Analysis using Python, enabling businesses to gain insights into their customer base and make data-driven decisions.
