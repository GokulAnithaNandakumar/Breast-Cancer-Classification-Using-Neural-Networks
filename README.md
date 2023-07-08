# Breast-Cancer-Classification-Using-Neural-Networks

<img width="631" alt="Screenshot 2023-07-08 at 1 29 08 PM" src="https://github.com/GokulAnithaNandakumar/Breast-Cancer-Classification-Using-Neural-Networks/assets/114865522/726a5883-3a73-4745-8d1f-62d85e653f42">


<img width="1092" alt="Screenshot 2023-07-08 at 1 28 22 PM" src="https://github.com/GokulAnithaNandakumar/Breast-Cancer-Classification-Using-Neural-Networks/assets/114865522/fa1f1b74-a33a-488e-a89a-4d6af9afdc5b">



ALGORITHM

1) Import the necessary libraries: numpy, pandas, matplotlib, sklearn.datasets, train_test_split, StandardScaler from sklearn, and tensorflow and keras from tensorflow.
2) Load the breast cancer dataset using sklearn.datasets.load_breast_cancer().
3) Create a pandas DataFrame from the dataset.
4) Preprocess the data by adding the target column, checking for missing values, and analyzing the distribution of the target variable.
5) Split the data into input features (X) and target variable (Y).
6 )Split the data into training and testing sets using train_test_split().
7) Scale the input features using StandardScaler.
8) Set the random seed for reproducibility.
9) Build the neural network model using keras.Sequential and add layers with the desired activation functions.
10) Compile the model with the chosen optimizer, loss function, and metrics.
11) Train the model using the training data, validating on a portion of the training data, and specifying the number of epochs.
12) Evaluate the model's performance on the testing data and print the accuracy.
13) Make predictions on the testing data and print the predicted probabilities and class labels.
14) Define the input data for prediction.
15) Transform and standardize the input data.
16) Make predictions on the input data and print the predicted probabilities and class label.
17) Display the accuracy and loss graphs using matplotlib.
