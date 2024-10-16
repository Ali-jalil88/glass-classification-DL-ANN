# Glass-Classification-DL-ANN
![Glass-Classification Deep Learning Project](https://github.com/Ali-jalil88/glass-classification-DL-ANN/blob/main/DALL%C2%B7E%202024-10-09%2013.56.12%20-%20A%20vibrant%20illustration%20of%20a%20deep%20learning%20process%20for%20glass%20classification%20using%20an%20Artificial%20Neural%20Network%20(ANN).%20The%20image%20shows%20a%20flowchart-like%20.webp)
### For Glass Classification using a Deep Learning Model (ANN), here’s a breakdown of the key topics:

#### 1- CSV Files & Data Splitting (pandas/sklearn):
- Load the dataset using pandas from a CSV file.
- Split the dataset into training and testing sets using train_test_split from the sklearn library.

#### 2- Data Preprocessing:
- Normalize the features using StandardScaler to standardize the input features for better convergence during training.

#### 3- Artificial Neural Network (ANN):
- A sequential model from Keras will be used to build the ANN with layers defined using Dense layers.
- Layers include input, hidden, and output layers, with activation functions such as ReLU (for hidden layers) and softmax (for multi-class classification).

#### 4- Optimizer (Adam):
- Adam is chosen as the optimizer, which is efficient for deep learning models, combining the advantages of both RMSProp and momentum.

#### 5- Loss Function:
- For multi-class classification, use categorical_crossentropy as the loss function.
#### 6- Metrics:
- Track performance using metrics like accuracy, precision, recall, and F1-score.
- Evaluation is done using the Keras model’s evaluate method.

#### 7- Epochs and Training:
- Train the model over a defined number of epochs, adjusting the batch size as needed.
- Use the training and validation data to observe how the model improves over epochs.

#### 8- Predictions:
- After training, make predictions on the test set using model.predict and evaluate the model's performance on unseen data.
## Links:
- **[Project Notebook](https://www.kaggle.com/code/alialarkawazi/glass-classification-dl-ann)**
- **[Dataset](https://www.kaggle.com/datasets/uciml/glass)**
