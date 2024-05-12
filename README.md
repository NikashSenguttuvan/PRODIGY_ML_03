# Cat and Dog Image Classification Using SVM<br>
This repository contains a machine learning project that focuses on classifying images of cats and dogs using a Support Vector Machine (SVM). The goal is to accurately identify and differentiate between images of cats and dogs using feature extraction followed by SVM classification.<br>

Project Overview:<br>
Objective: To develop a robust classifier that can differentiate between cat and dog images with high accuracy.<br>
Data: The dataset comprises numerous labeled images of cats and dogs. Images vary in size, background, and pose.<br>
Methodology: Utilizes Support Vector Machine (SVM) classifiers to manage binary image classification tasks with a focus on achieving optimal hyperplane separation between the two classes.<br>
Features:<br>
Image Preprocessing: Includes resizing, normalization, and augmentation techniques to prepare the images for classification.<br>
Feature Extraction: Utilizes techniques like Histogram of Oriented Gradients (HOG) to extract meaningful features from the images.<br>
SVM Classifier: Implements an SVM classifier, tuning parameters such as the kernel type, C (penalty parameter), and gamma to optimize performance.<br>
Model Evaluation: Uses metrics such as accuracy, precision, recall, and F1-score to evaluate the classifier's performance.<br>
Visualization: Includes confusion matrix and classification report visuals to help interpret the results.<br>
Tools and Technologies:<br>
Python: Primary programming language.<br>
Scikit-Learn: For implementing the SVM classifier and other machine learning utilities.<br>
OpenCV & skimage: For image processing.<br>
Matplotlib & Seaborn: For plotting and visualization.<br>
How to Use:<br>
Clone the Repository: Get a local copy of this repository to start working on the project.<br>
Install Dependencies: Install the required Python libraries using pip install -r requirements.txt.<br>
Execute the Notebooks: Run the provided Jupyter notebooks to process the images, train the SVM model, and evaluate the results.<br>
Dataset:<br>
link: https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset 
