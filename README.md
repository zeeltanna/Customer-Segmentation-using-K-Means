# **Customer Segmentation using K-Means Algorithm**
This project aims to categorize the customers using K-means machine learning model . The dataset includes features such as the Customer-ID, Gender, Age, Annual Income and Spending Score.

### **Data Description**

The dataset used in the analysis is called Mall Customers and it contains the following attributes:

	1. Customer ID: Includes the ID of the corresponding customer since names are kept confidential. (for privacy concerns)

	2. Gender: The gender of person - Either Male or Female

	3. Age: The age of the person in years(Integer Values).

	4. Annual Income: The annual income in form of thousand dollars(Eg: $15k).

	5. Spending Score: A metric score corresponding to the spending capacity of the customers. 

### **Steps Involved**

	1. **Data Preprocessing**:
    	- Load the dataset.
    	- Find inconsistencies and missing values in dataset and eliminate if any.
    	- Split the required data (Annual Income & Expenditure) from remaining dataset for analysis.

	2. **Calculate Optimal No. of Clusters**:
    	- Initialise an empty list for storing WCSS results
    	- Create a K-means model and fit the data according to the model.
		- Determine the WCSS value which gives the optimal number of clusters required and plot an Elbow Point Graph. 

	3. **Model Training**:
    	- Train the K-Means model with predefined parameter of no. of clusters i.e,5
    	- Return a label for each datapoint based on their clusters and print the results.

	4. **Visualization**:
    	- Plot a scatter graph containing 5 different clusters each representing different characteristics such as {High Income, High Spending}, {Low Income, High Spending}.

### **Results**
As a result of analysis the clusters can be categorised into 4 categories:		
		
1. High Income, High Spending
2. Low Income, Low Spending
3. High Income, Low Spending
4. Low Income, High Spending

 		- Cluster 1: Represents customers that have Normal Spending Score and Normal Annual Income.
		- Cluster 2: Represents customers that have High Spending Score and High Annual Income.
 		- Cluster 3: Represents customers that have Low Spending Score and High Annual Income.
		- Cluster 4: Represents customers that have Low Spending Score and Low Annual Income.
 		- Cluster 5: Represents customers that have High Spending Score and Low Annual Income.



