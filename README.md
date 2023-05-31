# DSProjectmpg

This repository contains code for analyzing and exploring the Miles Per Gallon (MPG) dataset, which provides information on various car models and their fuel efficiency. The code is written in Python and utilizes libraries such as pandas, seaborn, matplotlib, and plotly for data manipulation, visualization, and analysis.

## Introduction to the dataset

The MPG dataset is a valuable resource for analyzing the fuel efficiency of different automobiles. It contains information on car models, their attributes, and corresponding fuel efficiency measured in miles per gallon. By studying this dataset, we can gain insights into the factors that influence fuel consumption and identify trends in automotive technology over time.

## Dataset Information

- Dataset Link: [Auto MPG Dataset](https://www.kaggle.com/datasets/uciml/autompg-dataset)

1. Title: Auto-Mpg Data
2. Sources:
   - Origin: This dataset was taken from the StatLib library maintained at Carnegie Mellon University. The dataset was used in the 1983 American Statistical Association Exposition.
   - Date: July 7, 1993

3. Past Usage:
   - Quinlan, R. (1993). Combining Instance-Based and Model-Based Learning. In Proceedings on the Tenth International Conference of Machine Learning, 236-243, University of Massachusetts, Amherst. Morgan Kaufmann.

4. Relevant Information:
   - This dataset is a slightly modified version of the dataset provided in the StatLib library. It contains data on city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 continuous attributes.

5. Number of Instances: 398
6. Number of Attributes: 9 including the class attribute

## Code Overview

The code provided in this repository performs the following tasks:

1. Loads the necessary libraries and imports the MPG dataset from the UCI Machine Learning Repository.
2. Performs exploratory data analysis (EDA) to gain insights into the dataset's structure and content.
3. Cleans the data by handling missing values, removing duplicates, and dropping unnecessary columns.
4. Visualizes the data using various plots such as bar plots, box plots, histograms, and scatter plots.
5. Saves the final processed DataFrame as a CSV file named `final_df.csv`.

## Usage

1. Clone the repository:

```shell
git clone <repository-url>
