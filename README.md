# Classification_with_Deep_Learning

# Introduction
## Goal 🎯
The Objective is to follow the universal workflow of DLWP 4.5 for any dataset and restricting models to 
sequential Dense and Dropout layers.
<br>The Universal workflow to follow is:
-  Defining the problem and assembling a dataset
-  Choosing a measure of success
-  Deciding on an evaluation protocol
-  Preparing your data
-  Developing a model that does better than a baseline
-  Scaling up: developing a model that overfits
-  Regularizing your model and tuning your hyperparameters


## About Dataset

Dataset (UCI Machine Learning repository) - <a href = "https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+%28Sonar%2C+Mines+vs.+Rocks%29">Connectionist Bench (Sonar, Mines vs. Rocks) Data Set.</a> 

##### Problem : 
The task is to train a network to discriminate between sonar signals bounced off a metal cylinder and those bounced off a roughly cylindrical rock.

It is a good test dataset for neural networks because all of the input values are numerical and have the same scale.

We will evaluate the developed models using scikit-learn with 10-fold cross validation, in order to better tease out differences in the results.

The data set contains signals obtained from a variety of different aspect angles, spanning 90 degrees for the cylinder and 180 degrees for the rock.

Each pattern is a set of 60 numbers in the range 0.0 to 1.0. Each number represents the energy within a particular frequency band, integrated over a certain period of time. The integration aperture for higher frequencies occur later in time, since these frequencies are transmitted later during the chirp.

The label associated with each record contains the letter "R" if the object is a rock and "M" if it is a mine (metal cylinder). The numbers in the labels are in increasing order of aspect angle, but they do not encode the angle directly.
