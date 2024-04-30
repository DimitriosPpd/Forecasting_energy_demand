# Forecasting energy demand with a Feed-Forward Neural Network

This project is about forecasting energy consumption from smart meter data. The data is provided by CKW (https://www.ckw.ch/landingpages/open-data) and the anonymized ID used is '03466ed913455c281ffeeaa80abdfff6'.
The provided Notebook is part of my thesis called 'Low voltage low forecasting using ensemble methods'.

The notebook has 7 parts:

1.   Exploratory analysis of the data
2.   Data preparation for forecasting
3.   Create and train the model
4.   Forecasting
5.   Forecast evaluation
6.   Residual analysis
7.   Conclusions

## Installation

1. Clone the repository 
2. Install dependencies: requirements.txt

## Usage

To run the project install the packages provided in the first line of code and paste the filepath where you have stored the data on the second line: df = pd.read_parquet('filepath').

## Data

The data file needed for this project is stored on the folder 'Data'.
