# Project: Classification of Mixed CIFAR-10 Images

## Description
The model takes as input an image obtained as the average of two randomly selected samples from the CIFAR-10 dataset and must predict the categories of the two original components.

### Dataset Details
- The first image belongs to one of the following 5 categories:
  - Airplane
  - Automobile
  - Bird
  - Cat
  - Deer
- The second image belongs to one of the remaining 5 categories:
  - Dog
  - Frog
  - Horse
  - Ship
  - Truck

The model must output two labels, each belonging to one of the two defined groups (each with a range of 5 values).

## Evaluation Methodology
The model's performance will be measured using the following metric:
1. **Compute accuracy** for classifying both image components.
2. **Calculate the average** of the two obtained accuracies.

### Testing and Validation
- The metric must be evaluated on **10,000 inputs** generated from test data.
- The calculation must be repeated **10 times** to estimate the standard deviation.
- The standard deviation value must be reported.

## Input Data and Examples
A data generator will be provided below, along with some examples to support understanding of the task.

## Performance
The proposed model achieves an accuracy of 0.827
