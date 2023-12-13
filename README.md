# BloomsTaxonomyClassifier
This is a part of my undergraduate capstone project.

This is a machine learning classification model designed to categorize questions according to their Bloom's Taxonomy level. The model employs a customized feature extraction technique called TFPOS-IDF, which assigns higher weightage to words based on their position tags, particularly emphasizing verbs for this specific purpose. To achieve classification, the model utilizes an ensemble classifier that merges outcomes from three distinct ML classifiers—KNN, SVM, and Naive Bayes—using a hard voting mechanism.
