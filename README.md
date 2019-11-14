# Deep Learning Bootcamp Labs

## Lab 1: Intro to ML Packages: SKLearn
First, we'll walk through the [SKLearn tutorial](https://github.com/yala/deeplearning_bootcamp/blob/master/lab1/sklearn_tutorial.ipynb) together, and cover how to build and tune models on SKLearn. Next, you'll apply what you learned to two seperate exercises.


1. A natural language inference (NLI) exercise, where the [task](https://www.nyu.edu/projects/bowman/multinli/) is to predict if a pair of sentences constitute an entailement, a contradiction, or neither. Here is the [exercise](https://github.com/yala/deeplearning_bootcamp/blob/master/lab1/nli_excercise.ipynb) and [sample solution](https://github.com/yala/deeplearning_bootcamp/blob/master/lab1/nli_solution.ipynb).
2. A molecule propety prediction exercise, where the task is to predict log p of a molecule from it's molecular structure. Here are the [exercise](https://github.com/yala/deeplearning_bootcamp/blob/master/lab1/property_prediction_exercise.ipynb) and [sample solution](https://github.com/yala/deeplearning_bootcamp/blob/master/lab1/sample_property_prediction_solution.ipynb)

## Lab 2: Intro to ML Packages: PyTorch
First, we'll walk through the [PyTorch tutorial](https://github.com/yala/deeplearning_bootcamp/blob/master/lab2/pytorch_tutorial.ipynb) together, and cover how to build and tune models on neural networks in pytorch for Vision tasks. Next, we'll discuss how to apply these same ideas to NLP tasks in our [NLP tutorial](https://github.com/yala/deeplearning_bootcamp/blob/master/lab2/nlp_tutorial.ipynb). Finally, we'll close the day with two seperate exercises:

1. A molecule propety prediction exercise (but this time with neural networks), where the task is to predict log p of a molecule from it's molecular structure. Here are the [exercise](https://github.com/yala/deeplearning_bootcamp/blob/master/lab2/property_prediction_exercise.ipynb) and [sample solution](https://github.com/yala/deeplearning_bootcamp/blob/master/lab2/property_prediction_solution.ipynb)
2. A natural language inference (NLI) exercise (but this time with neural networks), where the [task](https://www.nyu.edu/projects/bowman/multinli/) is to predict if a pair of sentences constitute an entailement, a contradiction, or neither. Here is the [exercise]() and [sample solution]().

## Lab 3: Advanced Neural Networks and Transfer Learning for NLP

In this lab we'll slowly work through a CNN and RNN [tutorial](lab3/rnn_and_cnn_tutorial.ipynb). It be using the beer review sentiment analysis task as the motivating task.

As you follow the tutorial, make sure to take note of the key architectural and implementation aspects! After you have finished try making the following list of modifications:

1. Change all activations from `tanh`.
2. Change the learning rate, starting from high (~1) to small (~1e-6). How does this affect the training dynamics?
3. Give the MLP an extra layer.
4. Change max pooling to mean pooling in the RNN.
5. Give the CNN an extra convolutional layer.
6. Change from word inputs to character inputs. The tokens ["this", "is", "good"] should now be ["t", "h", "i", "s", " ", ...].

## Lab 4: Advanced Neural Networks and Transfer Learning for Vision and Final Exercises
Details to be posted on Thursday.

## Running the labs
The labs are Google Colaboratory notebooks, so just click the `View in Colaboratory` link on the notebook, and you should be all set!
To save your progress, you can copy the notebooks to your own google drive.

## Requirements:
Software: A modern web browser. This has been tested on Google Chrome, Firefox, and Safari.

Accounts: A Google Account. If you don't have one, please make a free one.
