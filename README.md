# Skin Disease Prediction using Xception Model

![Skin Disease Prediction](https://www.kaggleusercontent.com/datasets-images/ascanipek/skin-diseases/0/preview.png)

## Overview
This project aims to classify various skin diseases using the **Xception** deep learning model, achieving an accuracy of **96%**. The dataset used for training is sourced from [Kaggle](https://www.kaggle.com/datasets/ascanipek/skin-diseases).

## Features
- **Deep Learning Model:** Xception
- **Accuracy:** 96%
- **Dataset:** Skin Diseases Dataset from Kaggle
- **Preprocessing:** Image resizing, normalization, and augmentation
- **Frameworks Used:** TensorFlow, Keras
- **Deployment:** Can be used in real-world medical diagnosis applications

## Dataset
The dataset contains images of different types of skin diseases, including:
- Actinic keratoses
- Basal cell carcinoma
- Benign keratosis-like lesions
- Dermatofibroma
- Melanocytic nevi
- Melanoma
- Vascular lesions

Dataset link: [Kaggle Skin Diseases](https://www.kaggle.com/datasets/ascanipek/skin-diseases)

## Installation
Clone the repository and install the required dependencies:

```bash
 git clone https://github.com/your-username/skin-disease-prediction.git
 cd skin-disease-prediction
 pip install -r requirements.txt
```

## Model Training
To train the model, run the following command:

```bash
python train.py
```

## Prediction
To make predictions on new images:

```bash
python predict.py --image path/to/image.jpg
```

## Results
The model achieves an impressive **96% accuracy** on the test set, demonstrating its effectiveness in diagnosing skin diseases.

## Technologies Used
- Python
- TensorFlow/Keras
- OpenCV
- NumPy & Pandas
- Matplotlib & Seaborn

## Future Improvements
- Deploy the model using Flask/Django
- Improve accuracy by experimenting with different architectures
- Build a mobile application for real-time diagnosis


Feel free to contribute and improve the project! 🚀

