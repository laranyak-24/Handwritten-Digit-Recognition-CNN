# Handwritten Digit Recognition using Python, CNN and MNIST Dataset

1. PROJECT OVERVIEW

This project focuses on recognizing handwritten digits (0–9) using a Convolutional Neural Network (CNN). The model is developed using Python and TensorFlow/Keras and trained on the MNIST dataset.




2. OBJECTIVES

* To recognize handwritten digits automatically.
* To understand and implement CNN architecture.
* To train and evaluate a deep learning model.
* To achieve accurate digit classification.




3. DATASET

The MNIST dataset contains 70,000 grayscale handwritten digit images.

* Training images: 60,000
* Testing images: 10,000
* Image dimensions: 28 × 28 pixels
* Classes: Digits 0 to 9




4. TECHNOLOGY USED

* Python
* Google Colab
* TensorFlow and Keras
* NumPy
* Matplotlib
* MNIST Dataset




5. DATA PREPROCESSING

* Loaded the MNIST dataset.
* Normalized pixel values between 0 and 1.
* Reshaped images to include a grayscale channel.
* Prepared training and testing data.




6. CNN MODEL ARCHITECTURE

The CNN model consists of:

* Input Layer
* Convolutional Layer (32 filters)
* Max Pooling Layer
* Convolutional Layer (64 filters)
* Max Pooling Layer
* Flatten Layer
* Dense Layer (64 neurons)
* Output Layer (10 neurons with Softmax activation)




7. MODEL TRAINING

The model was trained using:

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Epochs: 5
* Batch Size: 128
* Validation Split: 10%




8. MODEL EVALUATION

The model was evaluated using the MNIST test dataset.

* Test Accuracy: 99.00%
* Test Loss: 0.02949




9. RESULTS

The CNN model successfully recognizes handwritten digits with high accuracy. Training and validation accuracy/loss graphs and a confusion matrix were generated to evaluate its performance.




10. SAMPLE PREDICTION

The model correctly predicted the sample handwritten digit.

* Actual Digit: 7
* Predicted Digit: 7
* Confidence: 100%




11. PROJECT FILES

* Handwritten_Digit_Recognition_CNN.ipynb – Jupyter Notebook
* mnist_handwritten_digit_recognition.py – Python source code
* mnist_digit_recognition.keras – Trained CNN model
* 11 screenshots showing code execution and outputs




12. CONCLUSION

This project demonstrates the application of Convolutional Neural Networks in handwritten digit recognition. The trained model achieved 99.00% test accuracy on the MNIST dataset, demonstrating effective digit classification.




13. FUTURE SCOPE

* Recognizing handwritten digits from uploaded images.
* Improving the model using advanced CNN architectures.
* Developing a web-based digit recognition application.
