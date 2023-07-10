

# Potato Plant Disease Classification using Convolutional Neural Networks

This project aims to classify images of potato plants into three categories: "Potato___Early_blight," "Potato___Late_blight," and "Potato___healthy" using convolutional neural networks (CNNs). The trained model can help in the early detection and diagnosis of potato plant diseases, enabling timely interventions for crop protection and improved yield.

## Dataset
The dataset used for training and evaluation consists of labeled images of potato plants collected from the "PlantVillage" directory. The dataset is divided into training, validation, and test sets, with a split of approximately 80%, 10%, and 10% respectively.

## Prerequisites
Make sure you have the following libraries installed before running the code:
- TensorFlow
- Keras
- Matplotlib

## Usage
1. Ensure that the dataset is stored in the "PlantVillage" directory.
2. Run the code provided in the Jupyter Notebook or Python script to train the CNN model on the potato plant images.
3. The model will be trained for the specified number of epochs, and the training and validation accuracy and loss curves will be displayed.
4. After training, the model will be evaluated on the test set, and the test accuracy will be reported.
5. Additional code snippets are provided to make predictions on individual images and visualize the results.

## Model Saving
The trained model can be saved for future use by calling the `model.save()` function. The saved model will be stored in the specified directory with 
the name "potatoes.h5".

## Results
The trained model achieves high accuracy in classifying the potato plant images into the respective disease categories.
The accuracy can be further improved by adjusting the hyperparameters, increasing the dataset size, or using more advanced network architectures.


Feel free to modify and use the code for your own purposes.

## Acknowledgments
This project was inspired by the need for accurate and timely identification of potato plant diseases to prevent yield loss and support sustainable 
agriculture. The dataset used for training the model was sourced from the "PlantVillage" dataset, which provides valuable resources for plant disease
research.

## References
[1] PlantVillage Dataset: [link to dataset] https://www.kaggle.com/datasets/arjuntejaswi/plant-village
[2] TensorFlow: [link to TensorFlow website](https://www.tensorflow.org/)
[3] Keras: [link to Keras documentation](https://keras.io/)
[4] Matplotlib: [link to Matplotlib documentation](https://matplotlib.org/)

