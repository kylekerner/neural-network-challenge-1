#  **neural-network-challenge-1**
### By: Kyle Kerner

In this program we assume we are working at a company that specializes in student loan refinancing.  Our goal is to help predict whether a borrower will repay their loan to allow a more accurante interest rate for the borrower.  With these assumptions we take a CSV file that contains information about previous student loan recipitents. 

Using the data we start by analyzing and exploring the data.  After, we set the target value to be equal to the credit_ranking.  Next, we split the features and targets sets into training and testing datasets.

Using the scikit-learn's StandardScaler, we scaled the features of the data.  After scaling the data, we compiled and evaluated the model using a neural network leveraging Tensorflow's Keras.  Using two hidden "relu" layers we created a Sequential model. After the model was made we compiled and fit the model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric. Using 50 epochs we fit the model and training data.  

Finally, we evalated the performance of the model exported the results to a keras file, then reloaded the model and made predictions on the testing data and saved the predictions to a DataFrame, saved to binary results and displayed a classification report with the y_test data and predictions.

# Sources
Source code provided in class as well as the use of Chat GPT to help with code direction was used in the making of the program.  