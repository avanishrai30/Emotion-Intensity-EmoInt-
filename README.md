# Models-EmoInt
Identify the intensity of emotions in text
## Problem Statement-
Develop methods to identify the intensity of emotions in text and submit a technical paper detailing the approaches used.

## Description
#### Background and Significance: 
Existing emotion datasets are mainly annotated categorically without an indication of degree of emotion. Further, the tasks are almost always framed as classification tasks (identify 1 among n emotions for this sentence). In contrast, it is often useful for applications to know the degree to which an emotion is expressed in text. This is the first task where systems have to automatically determine the intensity of emotions in tweets.

#### Task: 
Given a tweet and an emotion X, determine the intensity or degree of emotion X felt by the speaker -- a real-valued score between 0 and 1. The maximum possible score 1 stands for feeling the maximum amount of emotion X (or having a mental state maximally inclined towards feeling emotion X). The minimum possible score 0 stands for feeling the least amount of emotion X (or having a mental state maximally away from feeling emotion X). The tweet along with the emotion X will be referred to as an instance. Note that the absolute scores have no inherent meaning -- they are used only as a means to convey that the instances with higher scores correspond to a greater degree of emotion X than instances with lower scores.

## Table of Contents
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Folder Structure
1. **Data Folder** - Holds all the input files used for the project
    - a. **Train Data** - holds the data required to train the model
    - b. **Dev Data** - holds the data required to validate the model
    - c. **Test Data** - holds the data required to predict the unseen data

2. **IPYNB_Files Folder** - Holds all the necessary code required to run and test the model

3. **Report Folder** - Holds the reports where observations are noted

## Getting Started

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Python:** The code is written in Python. Make sure you have Python installed (version 3.8.16).
- **Libraries:** Install the required libraries using the following command:
  ##### pip install -r requirements.txt
- **Jupyternotebook:** Install jupyternotebook or any platform you are comfortable to run the code

## Usage

#### Train the Model:
- Open and run the LSTM- Deep learning Model.ipynb notebook in a Jupyter environment to identify the intensity of the emotion
- Open and run the Statistical Model.ipynb notebook in jupyter environment/any environment to understand the data more
