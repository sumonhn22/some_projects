# Customer-Segementation
Using K-means Clustering
### Medium.com Link for the story-
https://krantiwadmare10.medium.com/customer-segmentation-using-machine-learning-algorithm-ba027e0365a3

### Introduction
- K-means clustering is a type of unsupervised learning, which is used when you have unlabeled data (i.e., data without defined categories or groups).
- It is an iterative algorithm, that partitions the unlabelled data into K distint non-overlapping clusters.
- Each datapoint belongs to only one cluster. 
- It optimizes and tries to make the intra-cluster data points as similiar as possible while keeping the clusters as distint as possible.
- The sum of the square distances of each data point of a particular cluster and its centroid is at the minimum.
- Hence each clusters tries to attend its own nearest homogenity.

### Project Overview:
The analyses is done on the dataset available on the Kaggle website
https://www.kaggle.com/imkushwaha/customersegmentationdataset

The data-set has 3 main variables:
- 1.Age : Age of the customers in the mall, 
- 2.Annual Income(k$) : Annual income in 1000$,
- 3.Spending Score (1-100) : A score given to each customer depending on their spending.

### Installation:
This project requires Python 3.x and the following Python libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### BLog Story-
https://krantiwadmare10.medium.com/customer-segmentation-using-machine-learning-algorithm-ba027e0365a3

### RoadMap
- 1.Above libraries are loaded and read.
- 2.A distribution plot of each of the variables is created.
- 3.A violin distribution w.r.t the gender is created.
- 4.All three variables are grouped to find the highest customers in each variable.
- 5.Analyze the relationship between Annual Income and Spending Score wrt Age using scatter plot.
- 6.Apply Kmeans clustering to Age And Spending Score variables and visualize using scatter plot.
- 7.Apply Kmeans clustering to Annual Income And Spending Score variables and visualize using scatter plot.
- 8.Apply Kmeans clustering to all the three variables and visualize using a 3D plot.

### Conclusion:
The dataset has been clustered into 5 distinct non overlapping clusters.
