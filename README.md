# One_Neuron_To_Another

The main goal fo this project is to understand and implement the neural network in python.

## Datasets:
For this project, I have used Wisconsin Breast Cancer and Ecoli dataset. These datsets can be found in the Data sub folder. Below is the link provided:

1. [Cancer Data](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28original%29)
2. [Ecoli Data](https://archive.ics.uci.edu/ml/datasets/Ecoli)

When importing both of these dataset I normalized the values in each column, excluding the classification column. Also, in this process if the data had letters instead of numbers I converted it to numbers using the same normalization process.

## Algorithms:
For this project, I have implemented the Neural Network Model.

## Explanation:
The implementation for this algorithm is located in the Notebooks folder.

## Neural Network Model:

Neural networks are a set of algorithms, modeled loosely after the human brain, that are designed to recognize patterns. In case of the data sets chosen in this assignment neural network can be used to perform classification of the flower species and protein class for Iris and Ecoli data sets respectively. Neural network can be used to help group unlabeled data according to similarities among the example inputs, and then classify data when it has a labeled dataset to train on.

Each network consists of an input layer, a hidden layer, and an output layer. For this project I implemented a neural network class that featured forward and backward functions. Forward implementing forward propagation and backwards implementing backward propagation. For the neural network I chose the sigmoid function as my activation function. 

The detailed explanation of the implementation is clearly mentioned for each function in the notebooks for Cancer and Ecoli Datasets. 

## Conclusions:

Neural Network model implemented worked pretty well on both the datasets used. We can observe the accurate predictions made on the test data for each of the dataset. The number of iterations depends on the number of instances for each dataset to avoid overfitting the model. For Cancer dataset, the accuracy was around 97 percent adn for the Ecoli dataset the accuracy was 82 percent.

## Steps to execute:
1. Download the files from the github repository.
2. Get the allines.txt by unzipping the .zip file.
3. Place the file in data folder and place the data folder in notebooks folder. The notebooks folder should also have ipynb file as well.
4. Navigate to terminal and type "jupyter notebook"
5. Navigate to the folder where the notebooks are placed.
6. From the menu icon cell, select the notebook and click on Run all which will run the whole notebook from the first cell.

## Steps to follow:
## Neural Network Architectures
1. Set up a new git repository in your GitHub account
2. Pick two datasets from https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how neural networks can be used to accomplish the task for the specific dataset
5. Build a neural network to model the prediction process programmatically
6. Document your process and results
7. Commit your source code, documentation and other supporting files to the git repository in GitHub


### References:
https://towardsdatascience.com/how-to-build-your-own-neural-network-from-scratch-in-python-68998a08e4f6</br>
https://towardsdatascience.com/neural-network-on-iris-data-4e99601a42c8 </br>
https://towardsdatascience.com/how-to-build-your-own-neural-network-from-scratch-in-python-68998a08e4f6</br>

