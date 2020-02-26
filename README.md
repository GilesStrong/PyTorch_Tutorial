
# PyTorch Tutorial - Originally presented at IST's 6ªs Jornadas de Engenharia Física: 

[Presentation with GIFs](https://docs.google.com/presentation/d/1BbhZC7YhcVaJ3TL1EbW2QH4zNe2ZifWaqHzgyYssi1g/edit?usp=sharing)

## Running

The tutorial may either be run via Google Colab by clicking the blue badges, or directly by installing the appropriate Python modules yourself.

When running in Google Colab, it is best to change the runtime type to GPU: Runtime -> Change Runtime Type -> Hardware Accelerator -> GPU

## Overview

This tutorial is designed to present neural networks from a practical, coding perspective and focus on their implementation via [PyTorch](https://pytorch.org/).
Several notebooks are found in the `notebooks` folder:
1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/PyTorch_Tutorial/blob/master/notebooks/0_SGD_from_scratch.ipynb) SGD_from_scratch uses a single neuron for trivial classification and regression tasks on pseudodata, implementing backpropagation and weight updates manually in Numpy. 
1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/PyTorch_Tutorial/blob/master/notebooks/1_Basic_Classification.ipynb) Basic_Classification introduces PyTorch, using a non-trvial, but basic classification problem.
1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/PyTorch_Tutorial/blob/master/notebooks/2_Basic_Regression.ipynb) Basic_Regression again uses PyTorch to solve a basic regression problem using pseudo-data
1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/PyTorch_Tutorial/blob/master/notebooks/3_Classification_Application.ipynb) 3_Classification_Application is an example using real-world tabular data to training a simple classifier.
1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/PyTorch_Tutorial/blob/master/notebooks/4_Regression_Application_Exercise.ipynb) 4_Regression_Application_Exercise is an exercise using real-world tabular data to training a simple regressor.
1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/PyTorch_Tutorial/blob/master/notebooks/5_Regression_Application_Completed.ipynb) 5_Regression_Application_Completed is an example of how 4_Regression_Application_Exercise could be attempted, including a few tricks for training a regressor.
