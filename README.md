# Parameter_Optimization of SVM
College Assignment for UCS654

## About SVM and Parameter Optimization
Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Results
| Sample | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
|--------|---------------|-------------|---------|--------------|
| 0      | 1             | poly        | 0.54    | 0.25         |
| 1      | 2             | rbf         | 7.25    | 5.11         |
| 2      | 3             | poly        | 0.19    | 2.50         |
| 3      | 4             | rbf         | 1.64    | 7.45         |
| 4      | 5             | rbf         | 4.52    | 9.81         |
| 5      | 6             | sigmoid     | 6.71    | 1.00         |
| 6      | 7             | rbf         | 9.24    | 7.97         |
| 7      | 8             | sigmoid     | 3.41    | 3.43         |
| 8      | 9             | poly        | 6.39    | 4.73         |
| 9      | 10            | rbf         | 2.99    | 9.72         |


## Convergence Graph
![image](https://user-images.githubusercontent.com/79128432/233182260-289fd7f7-2d79-4164-aa8b-8511e2c2fe65.png)


# Dataset

Link: https://archive.ics.uci.edu/ml/datasets/Facebook+Live+Sellers+in+Thailand

## Facebook Live Sellers in Thailand Data Set

Abstract: Facebook pages of 10 Thai fashion and cosmetics retail sellers. Posts of a different nature (video, photos, statuses, and links). Engagement metrics consist of comments, shares, and reactions.

## Source:

Nassim Dehouche, Mahidol University International College, nassim.deh '@' mahidol.edu


## Data Set Information:

The variability of consumer engagement is analysed through a Principal Component Analysis, highlighting the changes induced by the use of Facebook Live. The seasonal component is analysed through a study of the averages of the different engagement metrics for different time-frames (hourly, daily and monthly). Finally, we identify statistical outlier posts, that are qualitatively analyzed further, in terms of their selling approach and activities.


## Attribute Information:

status_id
status_type
status_published
num_reactions
num_comments
num_shares
num_likes
num_loves
num_wows
num_hahas
num_sads
num_angrys


## Relevant Papers:

Nassim Dehouche and Apiradee Wongkitrungrueng. Facebook Live as a Direct Selling Channel, 2018, Proceedings of ANZMAC 2018: The 20th Conference of the Australian and New Zealand Marketing Academy. Adelaide (Australia), 3-5 December 2018.
Dehouche, N., 2020, Dataset on usage and engagement patterns for Facebook Live sellers in Thailand. Data in Brief, 30(105661).
Wongkitrungrueng, A., Dehouche, N., and Assarut, N., 2020, Live streaming commerce from the seller's perspective: implications for online relationship marketing. Journal of Martketing Management, 36(5-6).



## Citation Request:

Nassim Dehouche and Apiradee Wongkitrungrueng. Facebook Live as a Direct Selling Channel, 2018, Proceedings of ANZMAC 2018: The 20th Conference of the Australian and New Zealand Marketing Academy. Adelaide (Australia), 3-5 December 2018.
