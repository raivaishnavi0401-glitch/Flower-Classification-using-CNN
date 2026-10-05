# 🌸 Flower Classification using CNN and MobileNetV2

## 📌 Project Overview

This project uses Deep Learning to classify flower images into five different categories using a pretrained **MobileNetV2** model.

The project includes image preprocessing, data augmentation, model training, evaluation, and prediction on new flower images.

## 🌺 Flower Classes

The model classifies flowers into:

* Daisy
* Dandelion
* Rose
* Sunflower
* Tulip

## 📊 Dataset

The project uses the **Flowers Recognition** dataset from Kaggle.

* Total Images: 4,317
* Training Images: 3,021
* Validation Images: 648
* Testing Images: 648
* Image Size: 224 × 224
* Batch Size: 32

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* MobileNetV2
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* KaggleHub

## 🔄 Project Workflow

1. Imported the required libraries.
2. Downloaded the flower dataset using KaggleHub.
3. Defined the five flower classes.
4. Collected image paths and labels.
5. Divided the dataset into training, validation, and testing data.
6. Resized images to 224 × 224 pixels.
7. Applied MobileNetV2 preprocessing.
8. Used data augmentation such as flipping, rotation, and zoom.
9. Loaded pretrained MobileNetV2 with ImageNet weights.
10. Froze the pretrained model.
11. Added custom classification layers.
12. Compiled the model using the Adam optimizer.
13. Trained the model for 10 epochs.
14. Evaluated the model using test data.
15. Created accuracy and loss graphs.
16. Generated a classification report and confusion matrix.
17. Saved and loaded the trained model.
18. Used the model to predict a new flower image.

## 🧠 Model Architecture

The project uses **MobileNetV2** as the pretrained base model.

The final model contains:

* Data Augmentation
* MobileNetV2
* Global Average Pooling
* Dense Layer with 128 neurons
* ReLU Activation
* Dropout (0.3)
* Softmax Output Layer with 5 classes

## 📈 Model Evaluation

The model is evaluated using:

* Test Accuracy
* Test Loss
* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss
* Classification Report
* Confusion Matrix

## 🔮 Prediction

After training, the model is saved as:

`flower_mobilenetv2.keras`

The saved model can be loaded and used to classify a new flower image.

## ▶️ How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries.
3. Run the notebook cells step by step.
4. Download the dataset using KaggleHub.
5. Train the MobileNetV2 model.
6. Evaluate the model.
7. Upload a new flower image.
8. Get the predicted flower class.

## 🎯 Project Goal

The main goal of this project is to demonstrate how **Deep Learning and Transfer Learning** can be used for image classification and to identify different types of flowers from images.

## 📁 Files

* `Copy_of_flower_classification(using_cnn_mobilenet)(1).ipynb` — Main project notebook
* `flower_mobilenetv2.keras` — Trained model file

## 👩‍💻 Author

**Vaishnavi Rai**

