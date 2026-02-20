# Task-3---Cats-vs-Dogs
An SVM classifier was implemented on resized grayscale images to distinguish between cats and dogs, achieving approximately 65% classification accuracy.
Overview

This project implements a Support Vector Machine (SVM) classifier to distinguish between images of cats and dogs using the Kaggle Dogs vs Cats dataset. The images are preprocessed and converted into numerical feature vectors before training the model.

Dataset

The dataset used is the Dogs vs Cats dataset from Kaggle.
Each image file is labeled based on its filename:

cat.*.jpg → Cat (Label 0)

dog.*.jpg → Dog (Label 1)

Methodology

Images were loaded from a single directory.

Each image was converted to grayscale.

Images were resized to a fixed dimension.

Pixel values were flattened into feature vectors.

Data was split into training and testing sets (80–20 split).

A Linear Support Vector Machine (LinearSVC) model was trained.

Model performance was evaluated using accuracy, precision, recall, and F1-score.

Model Details

Image Size: 96 × 96

Maximum Images Used: 6000

Train-Test Split: 80% Training, 20% Testing

Classifier: LinearSVC

Results

The model achieved approximately 65% accuracy on the test dataset.
Precision and recall values were balanced across both classes.

Limitations

Raw pixel features were used instead of advanced feature extraction methods.

Performance can be improved using HOG features or deep learning models such as CNNs.

Future Improvements

Apply feature extraction techniques such as HOG.

Use dimensionality reduction (PCA).

Implement CNN-based classification for higher accuracy.
