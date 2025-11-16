# Image-Based Fresh Food Classification using CNN Transfer Learning

This repository contains the source code and documentation for a deep learning project submitted for the course Selected Topics in Computer Science (CoSc4132) at Debre Berhan University.
This project classifies the freshness of fruits using Convolutional Neural Networks and Transfer Learning.


Group Members:             ID

- Hailu worku -----------------0745
- Dawit demisu --------------- 0726
-Techale sime  ----------------0779
-Eden Mezgebe -----------------0730
-Ftsum Shewangzaw -------------0741

## 1. Project Overview


This project addresses the challenge of food waste by creating an automated system to classify the freshness of fruits (apples, bananas, and oranges) from images. We utilized a Transfer Learning approach with the MobileNetV2 architecture, implemented using TensorFlow and Keras  in a Google Colab  environment. The model was trained on the "Fresh and Stale Images of Fruits and Vegetables" dataset from Kaggle, which contains over 13,000 images across 6 distinct classes.

## 2. Results and Evaluation

The trained model demonstrated exceptional performance, achieving a high degree of accuracy and reliability.

### 2.1. Performance Metrics
The model's performance was evaluated using standard classification metrics, showing a validation accuracy of over 98%  and F1-scores consistently above 97% for all classes. This indicates that the model is highly effective and not biased towards any specific category.

### 2.2. Training Visualization
The learning process was visualized by plotting the accuracy and loss for both training and validation datasets over the training epochs. The graphs clearly show a healthy, upward trend in accuracy and a downward trend in loss, confirming an effective training session without significant overfitting.
 
 

### 2.3. Classification Report
A detailed classification report provides a breakdown of the model's performance per class, highlighting its strong precision and recall capabilities.

 
## 3. Live Demo (Extra Credit)

An interactive demo was developed using Gradio  to showcase the model's real-world application. The demo allows users to upload an image of a fruit and receive an instant classification of its freshness.


### Live Demo Link:
https://8805f8b6a7431f0bfe.gradio.live/

or  Gradio Public URL : Food_Freshness_Demo.ipynb - Colab

---

## 4. How to Run the Project

This project includes two Google Colab notebooks and a trained model file:

1.  Food_Freshness_Classification.ipynb: The main notebook for data preparation, model training, and evaluation.
2.  Food_Freshness_Demo.ipynb: The notebook for launching the interactive Gradio demo.
3.  food_classifier_model.h5: The saved, pre-trained model file.

To execute the project, run the notebooks sequentially in Google Colab. Ensure the dataset and the saved model (`.h5` file) are located in the correct Google Drive path as specified in the code.

