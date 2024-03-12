# deep-learning-challenge

## Overivew
### In this module we're working for a nonprofit foundation - Aplhabet Soup.   We're tasked to select the applicants for funding with the best chance of success in their ventures.   Using machine learning and neural networks, I'll use the features in the provided dataset to create a binary classifier that can predit wheter applicants will be successful in funded by Alphabet Soup. From Alphabet Soup, we received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

## Step 1: Preprocess the data 
###
1. Read in the charity_data.csv.
2. Drop the EIN and NAME columns.
3. Determine the number of unique values for each column.
4. Columns with more than 10 unique values, determine the number of data points for each unique value.
5. Use the number of data points for each unique value to pick a cutoff point to bin "rare' categorical variables.
6. Use pd.get_dummies() to encode categorical variables.
7. Split the reprocessed data into features array - X and Y.
8. Scale the training and testing features datasets by creating a StandardScaler to fit the training data then using transform function.

## Step 2: Compile, Train, and Evaluate the Model
###
Using TensorFlow, I design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup-funded organization will be successful based on the features in the dataset. 

1. Continue using the file in Google Colab in which you performed the preprocessing steps from Step 1.
2. Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.
3. Create the first hidden layer and choose an appropriate activation function.
4. If necessary, add a second hidden layer with an appropriate activation function.
5. Create an output layer with an appropriate activation function.
6. Check the structure of the model.
7. Compile and train the model.
8. Create a callback that saves the model's weights every five epochs.
9. Evaluate the model using the test data to determine the loss and accuracy.

## Step #3: Optimize the Model 
###
Using TensorFlow, will optimize the model to achieve a target predictive accuracy higher than 75%.

Use any or all of the following methods to optimize your model:
1. Adjust the input data to ensure that no variables or outliers are causing confusion in the model, such as:
2. Dropping more or fewer columns.
3. Creating more bins for rare occurrences in columns.
4. Increasing or decreasing the number of values for each bin.
5. Add more neurons to a hidden layer.
6. Add more hidden layers.
7. Use different activation functions for the hidden layers.
8. Add or reduce the number of epochs to the training regimen.
