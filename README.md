# Amazon-User-Segmentation-Using-K-Means-Clustering-
Segmentation of Amazon Users based on Purchase Rating, Age and Annual Income. K-Means Clustering method of Machine Learning is employed.

Data Points as in dataset:

Cus_ID (Customer ID)
Sex
Age
Annual Income
Purchase Rating

To employ K-Means, first the optimum no. of clusters is found using Elbow method by plotting WCSS vs no. of clusters graph.
Then K-Means model is defined and trained over dataset. The final clusters with datapoint and centroid is plotted using scatterplot.

Steps:

Importing libraries
Importing dataset
Finding No. of clusters using Elbow method
Defining and training K-Means model on dataset
Plotting the graph for visualization upon final clustering and analysis

As we see after implementation, Age vs Purchase Rating gives better picture on clustering than the Income vs Purchase Rating.
