# Predicting-the-presence-of-erythemato-squamos-disease-using-machine-learning
# MSc Data Science Thesis


# Aim and Scope of the Project
For the purpose of having a more accurate analysis of the diagnosis of the erythemato-squamous disease, we first reviewed the histological characteristics of the diseases, and then we used Decision Tree and K-Nearest Neighbor to exclude outlier data from the dataset. We find a threshold value using this approach for better outlier removal and the result was then tested. 
A dataset on dermatology containing 34 attributes, 33 of which are linear valued and one of them nominal was obtained from OpenML. 
In the said dataset constructed for this domain, the family history feature has the value 1 if any of these diseases has been observed in the family, and 0 otherwise. The age feature simply represents the age of the patient. Every other feature (clinical and histopathological) was given a degree in the range of 0 to 3. Here, 0 indicates that the feature was not present, 3 indicates the largest amount possible, and 1, 2 indicates the relative intermediate values.

# Research Objectives
1.	To assess how well different machine learning algorithms perform when used to diagnose and analyse erythemato-squamous disease
2.	To anticipate the erythemato-squamous disease differential diagnosis
3.	To predict the presence of erythemato-squamous disease using machine learning approach

# Methodology 
In this study, we aimed to investigate the effectiveness of various machine learning algorithms in the diagnosis and classification of skin conditions. The dataset used in this study contained information about various skin conditions, including seboreic dermatitis, psoriasis, lichen planus, chronic dermatitis, pityriasis rosea, and pityriasis rubra pilaris (Ilter et al., 1998). We applied logistic regression, decision trees, and random forest algorithms to the data and evaluated their performance using metrics such as accuracy, precision, recall, and the f1-score. Our goals were to examine the use of principal component analysis on the dataset, determine the most effective algorithm for accurately classifying skin conditions, and identify any limitations or areas for improvement.


## Summary of results

Summary of all the models’ scores

Based on the results above, it appears that all three models have similar performance in terms of accuracy, precision, and recall. They all have an accuracy of around 0.95, a precision of around 0.96, and a recall of around 0.96. The f1 score is also similar, with a value of around 0.89. 
Although the logistic regression and random forest models have similar scores, the decision tree model has lower scores across all metrics. Given these results, I would recommend the random forest model because it tends to have higher accuracy and generalizability compared to other models, especially when the data has many features or is unbalanced. Additionally, random forests are able to handle missing values and scale well with large datasets (Stekhoven and Bühlmann, 2012).
