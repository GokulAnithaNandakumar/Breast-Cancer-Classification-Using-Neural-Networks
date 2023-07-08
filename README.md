# Breast-Cancer-Classification-Using-Neural-Networks
Here's a breakdown of the code:

#Data loading and exploration:

The Breast Cancer Wisconsin dataset is loaded from scikit-learn's datasets module.
The data is converted to a pandas DataFrame for easier manipulation and exploration.
Information about the data, such as shape and missing values, is printed.
The target variable distribution is checked.

#Data preprocessing:

The dataset is split into features (X) and labels (Y).
The features are standardized using the StandardScaler from scikit-learn.
The dataset is split into training and testing sets using train_test_split from scikit-learn.

#Neural network model definition:

A sequential model is defined using Keras.
The model consists of a flatten layer to convert input data to a 1D array, a dense layer with ReLU activation, and a dense layer with sigmoid activation for binary classification.

#Model compilation and training:

The model is compiled with the Adam optimizer, sparse categorical cross-entropy loss, and accuracy metric.
The model is trained on the standardized training data, with a validation split of 0.1 and 10 epochs.
The training history is plotted to visualize the accuracy and loss.

#Model evaluation:

The model is evaluated on the standardized testing data, and the accuracy is printed.
Prediction on a new data point:

An example input data point is provided.
The input data is standardized using the same scaler used for training data.
The model predicts the probability of the input data belonging to each class (0 or 1).
The predicted class label is determined using the argmax function.
The predicted class label and interpretation are printed.
