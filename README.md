# Gender-Based Violence Analysis in Kenya

This project analyzes gender-based violence (GBV) data in Kenya. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/andrewmvd/violence-against-women-and-girls/data) and contains information on violence against women and girls worldwide. This project focuses specifically on filtering and analyzing the data for Kenya.

## Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Project Structure](#project-structure)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Gender-based violence is a critical issue that affects individuals worldwide. This project aims to shed light on the situation in Kenya by analyzing data on incidents of violence against both males and females. The analysis includes the number of victims by gender and the reasons for the violence.

## Data Source
The dataset used in this project is obtained from Kaggle:
- [Violence Against Women and Girls Dataset](https://www.kaggle.com/datasets/andrewmvd/violence-against-women-and-girls/data)

## Project Structure
The project directory contains the following files:
- `README.md`: Project documentation
- `gender_based_violence_analysis.ipynb`: Jupyter notebook containing the data analysis
- `data/`: Directory containing the original and processed datasets
  - `violence_data.csv`: Original dataset
  - `kenya_violence_data.csv`: Filtered dataset for Kenya

## Data Analysis
The analysis is performed in the `gender_based_violence_analysis.ipynb` notebook. The steps include:
1. Loading the dataset
2. Filtering the data for Kenya
3. Analyzing the number of victims by gender
4. Investigating the reasons for violence

## Findings
The key findings from the analysis are:
- The distribution of gender-based violence incidents by gender in Kenya
- The primary reasons for gender-based violence in Kenya

## Dependencies
The project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

You can install these dependencies using the following command:
```bash
pip install pandas numpy matplotlib seaborn jupyter
