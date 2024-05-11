# Dogs vs. Cats Classification with Support Vector Machine (SVM)

This repository contains code for classifying images of cats and dogs using a Support Vector Machine (SVM) classifier. The model is trained on the Kaggle dataset for dogs vs. cats classification.

## Dataset

The dataset used in this project can be found on Kaggle: [Dogs vs. Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)

## Requirements

- Python 3
- OpenCV (cv2)
- scikit-learn
- pandas

## Installation

1. Clone this repository
2. Navigate to the project directory
3. Ensure you have downloaded the Kaggle dataset and placed the training images in the `dogs-vs-cats/train/train` directory and the test images in the `dogs-vs-cats/test1/test1` directory

## Usage

1. Run the script `svm_classification.py` to train the SVM model and generate predictions.

```bash
python svm_classification.py
