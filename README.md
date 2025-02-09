# Amazon-User-Segmentation-Using-K-Means-Clustering-
Segmentation of Amazon Users based on Purchase Rating, Age and Annual Income. K-Means Clustering method of Machine Learning is employed.

**Data Points as in dataset:**

Cus_ID (Customer ID)
Sex
Age
Annual Income
Purchase Rating

**Steps:**

Importing libraries
Importing dataset
Finding No. of clusters using Elbow method
Defining and training K-Means model on dataset
Plotting the graph for visualization upon final clustering and analysis

To employ K-Means, first the optimum no. of clusters is found using Elbow method by plotting WCSS vs no. of clusters graph.
![image](https://github.com/user-attachments/assets/8cb550f8-8f2a-49f6-8e82-0f3ede3d684c)
![image](https://github.com/user-attachments/assets/93c4842c-117a-44aa-bfc0-3f8b56425565)

Then K-Means model is defined and trained over dataset. The final clusters with datapoint and centroid is plotted using scatterplot.

![image](https://github.com/user-attachments/assets/65d90a66-2153-46c0-8e08-f658bea340de)
![image](https://github.com/user-attachments/assets/b9b275de-aa9d-4f52-b484-f9f22a9bdc79)

As we see after implementation, Age vs Purchase Rating gives better picture on clustering than the Income vs Purchase Rating.


