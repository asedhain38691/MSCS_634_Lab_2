# MSCS_634_Lab_2

In this lab, I implemented and compared the performance of K-Nearest Neighbors (KNN) and Radius Neighbors (RNN) classifiers using the Wine dataset. From my experiments, I observed that the KNN model achieved very high accuracy, reaching 97.22% for smaller k values and even 100% accuracy for k = 11, 15, and 21. While this level of accuracy seems ideal, it may also indicate that the model could be overfitting to the training data, especially since real-world data rarely produces perfect results. Nonetheless, the consistent trend suggests that KNN was able to capture the underlying structure of the dataset effectively.

On the other hand, the RNN classifier performed poorly across all tested radius values, maintaining an accuracy of only 38.89%. This likely happened because the chosen radius values were not suitable for the scaled dataset, resulting in either too few or too many neighbors being considered for classification.

Overall, I found that KNN was much easier to tune and more reliable for this dataset, while RNN was highly sensitive to the choice of radius. This lab helped me understand how crucial parameter selection and feature scaling are in neighbor-based models, and it reinforced that high accuracy should always be evaluated carefully to ensure that the model generalizes well beyond the test data.
