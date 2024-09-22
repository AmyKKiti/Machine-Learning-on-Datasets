# Preparing Data for Training using Machine Learning Techniques.
This repository serves as the central resource for the course CSI 4106: Introduction to Artificial Intelligence, offered in the Fall 2024 semester at the University of Ottawa.

## 1. Analysis of Missing Values
All datasets are intended for multi-class classification tasks. Analyze the following datasets and produce a brief report on the missing/invalid attributes if any.
1. [Glass Identification dataset](www.kaggle.com/datasets/danushkumarv/glass-identification-data-set): Number of samples: 214, Number of attributes: 9, Number of classes: 7 (type of
glass like tableware, headlamps, vehicle) 
2. [Dermatology dataset](www.kaggle.com/datasets/olcaybolat1/dermatology-dataset-classification): Number of samples: 366, Number of attributes: 34, Number of classes: 6 (disorders
– psoriasis, seborrheic dermatitis, lichen planus, pityriasis rosea, chronic dermatitis,
and pityriasis rubra pilaris) 
3. [Maternal Health Risk](archive.ics.uci.edu/dataset/863/maternal+health+risk): Number of samples: 1013, Number of attributes: 6, Number of classes: 3 (risk level
– high, medium, low) 
4. [Car dataset](archive.ics.uci.edu/dataset/19/car+evaluation): Number of samples: 1728, Number of attributes: 6, Number of classes: 4 (unacceptable, acceptable, good, very good)
5. [Wine quality dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset): Number of samples: 4898, Number of attributes: 11, Number of classes: 11 (0 to 10) 
6. [16 personalities dataset](www.kaggle.com/datasets/anshulmehtakaggl/60k-responses-of-16-personalitiestest-mbt): Number of samples: 60K, Number of attributes: 60, Number of classes: 16 (personality type)
7. [Credit Score dataset](www.kaggle.com/datasets/parisrohan/credit-score-classification):
Number of samples: 100K, Number of attributes: 27, Number of classes: 3 (Good,
Standard, Poor)

## Attribute Analysis
- Determine which attributes lack informativeness and should be excluded to improve
the effectiveness of the machine learning analysis. If all features are deemed relevant,
explicitly state this conclusion.
- Examine the distribution of each attribute (column) within the dataset. Utilize
histograms or boxplots to visualize the distributions, identifying any underlying patterns
or outliers.

## Class Distribution Analysis
Investigate the distribution of class labels within the
dataset. Employ bar plots to visualize the frequency of instances for each class, and
assess whether the dataset is balanced or imbalanced

## Preprocessing
- For numerical features, determine the best transformation to use. Indicate the transformation that seems appropriate and why. Include the code illustrating how to apply
the transformation. For at least one attribute, show the distribution before and after
the transformation. See Preprocessing data.
- For categorical features, show how to apply one-hot encoding. If your dataset does
not have categorical data, show how to apply the one-hot encoder to the label (target
variable).

## Training and target data
- Set the Python variable X to designate the data and y to designate the target class. Make sure to select only the informative features.
- Split the dataset into training and testing sets. Reserve 20% of data for testing.
