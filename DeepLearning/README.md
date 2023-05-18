# Deep Learning Project

The project consists in predicting the outcome of the RainTomorrow variable which is composed by two values: 'Yes' if tomorrow it rains or 'No' otherwise.  
The PreProcessing.ipynb contains the code used to clean the data and in particular to handle the missing values which were the most problematic issue.  
We have chosen three ways to handle them. For each of them we have trained and optimized a neural network. Then, we have compared the results in order to choose the best solution for the task.  

Modeling_Oversampling.ipynb shows the effect of oversampling the majority class on the NN training while the Modeling_Undersampling.ipynb contains the code for the models optimization after the application of the undersampling technique to balance the two classes. 


The dataset is available [here](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)
