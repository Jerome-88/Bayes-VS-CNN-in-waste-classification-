This repository contains an image-based waste classification project that compares the performance of Convolutional Neural Network (CNN) and Naive Bayes models for classifying organic and anorganic waste. 
The project focuses on exploring how different machine learning approaches perform when applied to the same dataset and evaluation setup. The main goal of this project is to provide a simple experimental 
study on automated waste sorting, which can help reduce manual work and improve efficiency in waste management systems. Waste management remains a major challenge in Indonesia, especially in urban areas 
where large amounts of waste are generated every day. One of the main problems is waste segregation, which is still mostly done manually and often leads to inconsistent results. 
This project explores the use of computer vision and machine learning as an alternative approach to classify waste automatically based on visual characteristics such as shape, color, and texture.
Two different classification methods are implemented and compared:
Convolutional Neural Network (CNN)
CNN is used to directly learn visual features from raw images. This approach is well suited for image classification tasks and can capture spatial patterns that are difficult to design manually.
Naive Bayes
Naive Bayes is applied using features extracted from the images. While simpler and more interpretable, its performance is affected by the assumption that features are independent.
For simplicity, both models are implemented in a single script (main.py), which includes data preprocessing, model training, and evaluation.
