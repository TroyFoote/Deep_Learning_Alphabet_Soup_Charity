# Alphabet_Soup_Charity

## Project Description

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

### Requirements

* charity_data.csv

### Instructions

#### Preprocess the Data

1. Read in the charity_data_csv file into a Pandas DataFrame.
2. Determine the target and feature variables for your model.
3. Drop **EIN** & **NAME** columns.
4. Determine the number of unique values for each column. For those that have more than 10 unique values, determin the number of data points for each unique value.
5. Determine a cutoff point to bin 'rare' categorical variables together.
6. Use **get_dummies()** to encode categorical variables.
7. Split the data into a features array **X** and a target array **y**. Then split data into training and testing datastets.
8. Scale the training and testing datasets, then fit and transform.

#### Compile, Train and Evaluate the Model

Design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup-funded organisation will be successful based on the features in the dataset. Then  compile, train and evaluate your binary classification model to calculate the model’s loss and accuracy.

1. Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.
2. Create the first hidden layer and choose an appropriate activation function. If necessary, add a second hidden layer with an appropriate activation function.
3. Create an output layer with an appropriate activation function.
4. Check the structure of the model.
5. Compile and train the model.
6. Create a callback that saves the model's weights every five epochs.
7. Evaluate the model using the test data to determine the loss and accuracy.
8. Save and export your results to an HDF5 file. Name the file **AlphabetSoupCharity.h5.**

#### Optimise the Model

Optimise your model to achieve a target predictive accuracy higher than 75%.

Use any or all of the following methods to optimise your model:

1. Adjust the input data to ensure that no variables or outliers are causing confusion in the model, such as:
    * Dropping more or fewer columns.
    * Creating more bins for rare occurrences in columns.
    * Increasing or decreasing the number of values for each bin.
2. Add more neurons to a hidden layer.
3. Add more hidden layers.
4. Use different activation functions for the hidden layers.
5. Add or reduce the number of epochs to the training regimen.

Create a new Jupyter Notebook file and name it **AlphabetSoupCharity_Optimisation.ipynb.**

1. Import your dependencies and read in the charity_data.csv to a Pandas DataFrame.

2. Preprocess the dataset as you did in Step 1. Be sure to adjust for any modifications that came out of optimising the model.

3. Design a neural network model, and be sure to adjust for modifications that will optimise the model to achieve higher than 75% accuracy.

4. Save and export your results to an HDF5 file. Name the file **AlphabetSoupCharity_Optimisation.h5.**

#### Write a Report on the Neural Network Model

1. Overview of the analysis:
2. Results: 
Using bulleted lists and images to support your answers, address the following questions:

    * Data Preprocessing
        * What variable(s) are the target(s) for your model?
        * What variable(s) are the features for your model?
        * What variable(s) should be removed from the input data because they are neither targets nor features?

    * Compiling, Training and Evaluating the Model
        * How many neurons, layers, and activation functions did you select for your neural network model, and why?
        * Were you able to achieve the target model performance?
        * What steps did you take in your attempts to increase model performance?

3. Summary: 
Summarise the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

### Dependencies

* Google Colab 
* Python
* Pandas
* Scikit.learn
* tensorflow
* keras-tuner

### References
References
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/