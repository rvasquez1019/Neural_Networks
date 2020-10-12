# Neural_Networks Deep Learning Models

The CSV file contained more than 34,000 organizations that received various amounts of funding from Alphabet Soup over the years.  Within this dataset numerous of columns that capture metadata about each organization.  Applying the machine learning and neutral network model building, I created binary classifiers that were capable of predicting weather or not an applicant was successful of funding by Alphabet Soup.  

# Goals 

- Optimize model training and input data to achieve desired model performance.
- Import, analyze, clean, and pre-process a real world classification dataset.
- Select, design, and train a binary classification model.

# Analyse 
I was not able to optimize a predictive accuracy higher than 75%.  The predictive accuracy of my model was 53.24%, significance that this model is able to predict the success of a venture paid by Alphabet Soup 53% of the time.  

My model has two hidden layers with 28 and 14 and 6 neurons.  The first and second hidden layers use the relu activation function to identify non-linear characteristics from the input values.  The sigmoid function is used on the output layer.  The model is compiled by the binary-crossentropy loss function, adam optimizer, and accuracy metrics.

I increased the number of epochs to 100 but the percentage did not change much so I left the epochs at 50.  

