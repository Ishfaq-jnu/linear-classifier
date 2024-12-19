# linear-classifier

This code implements a Linear Support Vector Classifier (SVM) to classify images from a dataset, such as the Kaggle Dogs vs. Cats dataset, based on their color histograms. Key steps include:

Feature Extraction: A 3D color histogram is computed from the HSV color space for each image to serve as the feature vector.
Data Preparation: Images are labeled and split into training (75%) and testing (25%) datasets.
Model Training: A LinearSVC model is trained on the extracted color histogram features.
 The trained classifier is tested on the testing data, and the performance is reported using a classification report.
This approach demonstrates using simple features (color histograms) and a linear classifier for image classification tasks.
