
# Prediction of COVID-19 from Chest X-ray Images 
The project involved developing and training a convolutional neural network (CNN) using Keras with TensorFlow backend to classify chest X-ray images and determine whether patients were infected with COVID-19 or not. Matplotlib was utilized for data visualization, while TensorFlow 2.0 was employed for data preprocessing and augmentation.

The CNN model architecture comprised sequential layers, including convolutional, pooling, dropout, and dense layers with ReLU activation, followed by an output layer with sigmoid activation. The dataset contained X-ray images of lungs from both non-COVID and COVID-infected patients, sourced from Kaggle.

For model evaluation, training, validation, and test set accuracies were selected as metrics. The Adam optimizer with a learning rate of 0.001 was utilized for gradient descent during training. The project was executed within the Google Colab environment.

The model achieved promising results:

Training Set Accuracy: 98.41%, Loss: 0.0490
Validation Set Accuracy: 97.51%, Loss: 0.0759
Test Set Accuracy: 94.83%, Loss: 0.1141

INSPIRED PROJECT FROM RESEARCH PAPER







