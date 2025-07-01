# Simple Image Classifier

A deep learning project to classify images of cats and dogs using a Keras model trained with [Teachable Machines](https://teachablemachine.withgoogle.com/).

## Features
- Classifies images as either "cat" or "dog"
- Pre-trained Keras model (`keras_model.h5`)
- Model evaluation with accuracy, precision, recall, F1-score

## Contents
- `keras_model.h5` — Pre-trained Keras model
- `labels.txt` — Class labels
- `task.ipynb` — Jupyter notebook for single image and evaluation
- The dataset used for the training can be found [here](https://www.kaggle.com/datasets/tongpython/cat-and-dog)

## Installation
1. **Install dependencies** (Python 3.8–3.10):
```bash
pip install tensorflow==2.12.1 Pillow numpy keras scikit-learn matplotlib tqdm
```
2. **Clone the repository**
```bash
git clone https://github.com/itsbaraa/Simple-Image-Classifier.git
```
  
## Output
```
Class: Cat
Confidence Score: 1.0
```
## Evaluation
```
              precision    recall  f1-score   support

        cats       0.97      0.97      0.97      1011
        dogs       0.97      0.97      0.97      1012

    accuracy                           0.97      2023
   macro avg       0.97      0.97      0.97      2023
weighted avg       0.97      0.97      0.97      2023
```
