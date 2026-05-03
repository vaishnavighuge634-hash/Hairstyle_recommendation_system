# Hairstyle Recommendation System using CNN

## Project Overview

This project is a **Deep Learning-based Hairstyle Recommendation System** that suggests suitable hairstyles based on:

* Face Shape
* Hair Type
* Hair Length

The model is built using a **Convolutional Neural Network (CNN)** and trained on a structured dataset.

---

## Problem Statement

Choosing the right hairstyle is difficult without expert advice. This project aims to automate hairstyle recommendations using deep learning.

---

## Dataset

* Total Records: 599
* Features:

  * Face Shape
  * Hair Type
  * Hair Length
* Target:

  * Recommended Hairstyle

---

## Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib

---

## Model Architecture

* Conv1D Layer (32 filters)
* MaxPooling Layer
* Conv1D Layer (64 filters)
* Flatten Layer
* Dense Layer
* Output Layer (Softmax)

---

## Results

* Training Accuracy: 100%
* Testing Accuracy: 100%

Note: High accuracy may indicate overfitting due to small dataset.

---

## Visualization

Accuracy vs Epoch graph is used to analyze model performance.

---

## Future Improvements

* Use real image dataset
* Deploy as web app
* Add more features (age, gender, etc.)

---

## How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/hairstyle-recommendation-cnn.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the notebook in Google Colab or Jupyter Notebook

---

## Author

Vaishnavi Ghuge

---

## ⭐ If you like this project, give it a star!
