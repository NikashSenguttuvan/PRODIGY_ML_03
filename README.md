# Cat and Dog Image Classification Using SVM
This repository contains a machine learning project that focuses on classifying images of cats and dogs using a Support Vector Machine (SVM). The goal is to accurately identify and differentiate between images of cats and dogs using feature extraction followed by SVM classification.

Project Overview
Objective: To develop a robust classifier that can differentiate between cat and dog images with high accuracy.
Data: The dataset comprises numerous labeled images of cats and dogs. Images vary in size, background, and pose.
Methodology: Utilizes Support Vector Machine (SVM) classifiers to manage binary image classification tasks with a focus on achieving optimal hyperplane separation between the two classes.
Features
Image Preprocessing: Includes resizing, normalization, and augmentation techniques to prepare the images for classification.
Feature Extraction: Utilizes techniques like Histogram of Oriented Gradients (HOG) to extract meaningful features from the images.
SVM Classifier: Implements an SVM classifier, tuning parameters such as the kernel type, C (penalty parameter), and gamma to optimize performance.
Model Evaluation: Uses metrics such as accuracy, precision, recall, and F1-score to evaluate the classifier's performance.
Visualization: Includes confusion matrix and classification report visuals to help interpret the results.
Tools and Technologies
Python: Primary programming language.
Scikit-Learn: For implementing the SVM classifier and other machine learning utilities.
OpenCV & skimage: For image processing.
Matplotlib & Seaborn: For plotting and visualization.
How to Use
Clone the Repository: Get a local copy of this repository to start working on the project.
Install Dependencies: Install the required Python libraries using pip install -r requirements.txt.
Execute the Notebooks: Run the provided Jupyter notebooks to process the images, train the SVM model, and evaluate the results.
