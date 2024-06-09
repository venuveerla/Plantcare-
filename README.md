# Plantcare
### Introduction
PlantCare+ is a machine learning project developed to detect plant diseases from images of plant leaves. This project leverages Convolutional Neural Networks (CNN) and transfer learning with MobileNetV2 to accurately classify images of healthy and diseased plants. The system aims to assist farmers and plant enthusiasts in identifying plant health issues and taking appropriate measures.

### Dependencies
The project requires the following libraries:
1. Python 3.x
2. OpenCV
3. TensorFlow/Keras
4. NumPy
5. Matplotlib
6. Seaborn
7. Scikit-learn
8. Pandas
### Model Training

#### Convolutional Neural Network (CNN):

A CNN is built with Conv2D, MaxPooling2D, Flatten, and Dense layers.
The model is compiled and trained on the preprocessed data.

#### MobileNetV2:
A pre-trained MobileNetV2 model is used with frozen layers.
A new model is created on top with GlobalAveragePooling2D and Dense layers.
The model is compiled and trained on the preprocessed data.
### Accuracy Scores
1. CNN Model: 83.56%
2. MobileNetV2 Model: 95.35%
