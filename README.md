# ACT_Coursework_2
Second Coursework Assignment for Advanced Computational Techniques 2025/26

<br>

## Project Outline

- Select a dataset.
- Solve the problem using traditional machine learning techniques.
- Solve the problem using a neural network.
- Answer the following questions:
    - Q1) Why did you choose this traditional ML technique and how well does it solve the problem?
    - Q2) Why did you choose this NN technique and how well does it solve the problem compared to the other technique?
    - Q3) How do choices about (i) amount of training data and (ii) balance of classes in a classification problem affect the performance of a neural network?

<br>

## About the Dataset

CERN Subatomic Particles Dataset: 

https://www.kaggle.com/datasets/omidbaghchehsaraei/cern-subatomic-particles-dataset

This is a subset of the CERN OpenData DoubleMu/RunA_2011 dataset, as the full dataset is 4.8 TiB (over 5 TB of storage).

__Features of the dataset:__

- 40,000 samples
- 21 features (18 numerical, 2 binary classes)
- 1 target feature (binary classes)

The first 3 columns are index, run number, and event number. These are useful for tracking the data but irrelevant to the underlying physics.

__The Problem:__

Using the properties from columns 4-21, determine whether the resulting particle will be a J/Psi meson or an Upsilon meson.

This is a binary classification problem using a tabular dataset.

<br>

## Approach 1 - Traditional Machine Learning Techniques

Traditional ML technique chosen: Decision Tree

<br>

## Approach 2 - Neural Networks

Neural network built using PyTorch with 2 layers, 64 neurons per layer.


<br>

## Research Question - Investigate Changes in Neural Network Performance

Investigating the effects of changes in:

i) amount of training data
ii) balance of classes

on the performance of the neural network.
