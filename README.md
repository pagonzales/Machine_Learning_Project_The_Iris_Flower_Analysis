#  Unsupervised Machine Learning Project (The Iris Flower Analysis)
## Project Objective
The primary objective of this project is to segment different species of the Iris flowers from the dataset using unsupervised machine learning, specifically clustering techniques. The goal is to analyze if clustering algorithms (like KMeans) can effectively separate and identify species without using their labels, simulating a scenario where we lack pre-labeled data.
## Data used
- <a href = "https://github.com/pagonzales/Machine_Learning_Project_The_Iris_Flower_Analysis/blob/main/iris_dataset.csv">Dataset</a>
## Questions
- Can clustering techniques like KMeans identify natural groupings in the Iris dataset?
- How well does the clustering output align with actual species labels?
- What is the optimal number of clusters for this dataset?
- How do different features (petal length, sepal width, etc.) contribute to the clustering result?

## Process
- Data Preparation
  - Loaded the Iris dataset
  - Extracted numerical features for clustering.
- Plot the data and look for the clustered (unscaled data)
- Then, use standardization of the variables to plot again the clustered data.
- Clustering with KMeans
- Take advantage of the Elbow method to look for the number of clustering
- Plot then compare the different clustering values produced from Elbow method
- Compare the result with the actual data

## Images
- The Elbow Method plot:
  ![Elbow](https://github.com/user-attachments/assets/d827bd56-9743-472b-8e64-d65e758eee56)
- Clustered plot with 2 clusters
  ![k2](https://github.com/user-attachments/assets/9aa2dc03-cff8-4d8d-9ba7-b0617ea4bf0a)
- Clustered plot with 3 clusters
![k3](https://github.com/user-attachments/assets/6a9949d3-94a8-43f8-a99c-3bbff859e18e)
- Clustered plot with 5 clusters
  ![k5](https://github.com/user-attachments/assets/5039649a-8b6c-4f56-a9f2-290dd72a9bef)

## Project Insights
- Cluster Alignment: KMeans was able to segment the Iris dataset into meaningful clusters that closely correspond to actual species, which is clearly separable.
- Elbow Plot: The elbow method suggested 3 as the optimal number of clusters, which aligns with the known number of species.
- Scalability: The approach demonstrates how unsupervised clustering can be effective even when labels are not available, and can be scaled to other biological or classification tasks.
## Final conclusion
This shows us that:

- The Elbow method is imperfect (we might have opted for 2 or even 4)
- K-means is very useful in moments where we already know the number of clusters - in this case: 3
- Biology cannot be always quantified (or better),quantified with k-means! Other methods are much better at that.
Finally, you can try to classify them (instead of cluster them, now that you have all the data)!
