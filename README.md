# Deep-Learning-Project-1
## Handwritten Digit Classification

Language - Python

IDE Jupyter Notebook

For this task, we will be working on the MNIST database. The MNIST data is a database of handwritten digits from 0 to 9. The database contains 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images. The task is to create an ANN model for identifying the digit from the handwritten images.

The following operations are done:

1. Load the database to variable named digit_mnist using the Keras inbuilt datasets.
2. Import data to create X_train_full, y_train_full, X_test and y_test variables
3. Normalize the data
4. Create a validation set of 6000 images
5. Create an ANN model with two dense layers of 200 and 100 neurons
6. Compile and train the model for 60 epochs
7. Plot the loss and accuracy against epoch
8. Evaluate the model accuracy on the test dataset
9. Predict the digit for the first 5 records of the test dataset
10. Verify the predictions with the actual images.


## Fashion Objects Classification

Language - Python

IDE Jupyter Notebook

For this task, we will be working on the FASHION_MNIST database. The FASHION_MNIST data is a database of 10 different kinds of fashion objects corresponding from 0 to 9:

0 - T-shirt/Top; 
1 - Trouser; 
2 - Pullover; 
3 - Dress; 
4 - Coat; 
5 - Sandal; 
6 - Shirt; 
7 - Sneaker; 
8 - Bag; 
9 - Ankle Boot.

The database contains 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images. The task is to create an ANN model for identifying the fashion object from the images.

The following operations are done:

1. Load the database to variable named fashion_mnist using the Keras inbuilt datasets
2. Import data to create X_train_full, y_train_full, X_test and y_test variables
3. Normalize the data
4. Create a validation set of 6000 images
5. Create an ANN model with two dense layers of 200 and 100 neurons
6. Compile and train the model for 60 epochs
7. Plot the loss and accuracy against epoch
8. Evaluate the model accuracy on the test dataset
9. Predict the object for the first 5 records of the test dataset
10. Verify the predictions with the actual images.
