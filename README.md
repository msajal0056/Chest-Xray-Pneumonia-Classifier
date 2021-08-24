# Chest-Xray-Pneumonia-Classifier
CNN Model to classify between Xray of a person - Whether it's Normal or Pneumonia. It uses Transfer Learning. The model uses a pre-trained Inception Network model and has taken the "mixed7" layer as the last layer, followed by a Dense layer with 1024 neurons and ReLu activation function. The Last layer is a Sigmoid Layer. The Model predicts 0 : Normal and 1 : Pneumonia. We got 91.35% test accuracy.
Data Source: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
