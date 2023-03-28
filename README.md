# WineQualtiy-PredictionCode
This code is an implementation of a neural network-based model for predicting the quality of wine, which involves data preprocessing, normalization, and the creation of a neural network model.

Here is a step by step explanation of the code:

The numpy and pandas libraries are imported.
The winequality-red.csv file is read using the pd.read_csv() function and stored in a dataframe called df. The df.info() and df.head() commands are used to print the information about the dataframe and the first five rows of the dataframe respectively.

The tensorflow and keras libraries are imported.
The df.sample() function is used to randomly select 75% of the rows from the dataframe and store it in train_df. The remaining 25% rows are stored in val_df.
The training and validation data is normalized.
The data is split into input (X) and output (Y) variables.
The shape of the input data is calculated.
A neural network model is created.
The model.summary() function is used to display a summary of the created neural network model.
A test data point is selected and preprocessed.

The created neural network model is used to make predictions on test data points.
