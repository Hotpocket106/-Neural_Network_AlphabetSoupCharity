# AlphabetSoupCharity

AlphabetSoupCharity is a neural network application designed to predict charitable donations based on a set of input features. The model is built using TensorFlow.

## Format Data

![1](https://github.com/Hotpocket106/-Neural_Network_AlphabetSoupCharity/blob/main/Image/1.png?raw=true)

First after reviewing the dataset we need to filter unnecessary values in this case are the EIN and NAME columns.
Next as the screenshot showing above we need to convert object data into numerical data type and group certain columns to prevent overfitting for this module.

![2](https://github.com/Hotpocket106/-Neural_Network_AlphabetSoupCharity/blob/main/Image/2.png?raw=true)
![3](https://github.com/Hotpocket106/-Neural_Network_AlphabetSoupCharity/blob/main/Image/3.png?raw=true)
Then we encode the data into numerical values and now we are ready to scale and train the data.

## Model fitting and training

Now we are ready to train this dataset using TensorFlow, we first need to scale the data.
![4](https://github.com/Hotpocket106/-Neural_Network_AlphabetSoupCharity/blob/main/Image/4.png?raw=true)

we set up 2 hidden layers and each containing 80 and 30 nodes using Relu activation method.
From the summary we can tell that the total parameters are 6061 and now it ready to comile and fit on to the model. 

# Summary

AlphabetSoupCharity is a neural network application designed to predict charitable donations based on a set of input features. The model is built using a popular deep learning framework and is trained on a dataset of a certain number of examples. To use the application, one must first clone the repository and install the required dependencies, then train the model and make predictions. Contributions to the project are welcome and questions or issues can be directed to the specified contact information.
In this Module we are getting 64% of the accuarcy which mean this training model is not very accuarte predictions in the real world practise we either need a different dataset or use a different method for the prediction.
