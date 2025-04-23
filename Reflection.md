Which insights did you gain from your EDA? Were any columns highly correlated? If so, name them.
Most of the topics of music followed a similar distribution style. I did not find much correlation, I could have done  a better job at picking features that would better help me with these conclusions.

How did you determine which columns to drop or keep? If your EDA informed this process, explain which insights you used to determine which columns were not needed. 
Based on the example that was provided in class, it helped me come to the conclusion that both length and age were not necessary. These would often lead to misclassifications.

What was the optimal number of clusters in your cluster model? Explain how you determined this value.
My optimal number of clusters in my cluster model was 9, I determined this value by running a range of cluster validity metrics, including the Elbow method and Silhouette scores and 9 was the highest I got.

Take a look at the respective songs that fell into your clusters. Describe these clusters in human terms to the best of your ability using the columns in your dataset (for example high-gospel songs, low-gospel songs, etc). Feel free to listen to these songs as well to get a sense of what nuance your algorithm picked up on.
My clusters did not exactly divide the songs into distinct categories; instead, they were quite mixed.

Take a look at the clusters that your algorithm assigned to your test samples. Based on these clusters, which songs would you recommend to this user?
Again, I could have done a better job at this as the feature selection process could have been improved to yield more meaningful recommendations.
