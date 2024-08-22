# PRODIGY_ML_03
**Cat vs. Dog Image Classification with SVM**
This project implements a machine learning pipeline to classify images of cats and dogs using a Support Vector Machine (SVM). The dataset used is the popular Cats vs. Dogs dataset from Kaggle, containing labeled images of cats and dogs. The workflow includes the following steps:

Data Preprocessing: Images are resized to 128x128 pixels, normalized, and flattened to create feature vectors suitable for SVM classification.

Model Training: An SVM with an RBF kernel is trained on the preprocessed images to differentiate between cats and dogs. The model is saved using pickle for later use.

Image Prediction: Users can input an image, which is preprocessed similarly to the training data, and the trained SVM model predicts whether the image is of a cat or dog.

Image Display: The input image is displayed alongside the prediction result, providing a visual confirmation of the classification.

Dependencies
Python 3.x
OpenCV
Scikit-learn
Matplotlib
Pickle
Usage
Train the model on the dataset and save it.
Use the provided script to predict and display results for new images.
