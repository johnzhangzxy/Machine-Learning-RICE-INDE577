# Stroke_Data_Explore

Members: John Xiaoyu Zhang, Siling Liu

This is a course related project that delves into the analysis of a stroke dataset, aiming to extract insights and enhance our comprehension of the data. We achieve this by processing the data, creating visualizations, and examining relationships between various variables.

The dataset comprises both categorical and numerical data, differing among individuals. Some categorical variables, such as gender and residence type, appear to be irrelevant. However, age, heart disease, and average glucose level exhibit a degree of correlation with stroke incidence. It is crucial to acknowledge the data's imbalance, with only a small percentage of stroke cases present. This might result in less accurate predictions when determining stroke risk, but the analysis remains a valuable reference for stroke prevention efforts.

To tackle the issue of imbalanced data, we implemented an oversampling strategy to augment the sample size of stroke cases in the training data.

We selected KNN, bagging, random forest, logistic regression, and neural network methods to train and predict our models, as well as conducting accuracy analysis to gain a deeper understanding of the models. These techniques produced promising outcomes, particularly in identifying individuals who are not at risk of stroke.

After constructing our models and comparing them based on mean accuracy scores, we discovered that KNN and neural network approaches delivered superior results. 



