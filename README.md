
# Mental Health in the Technology Industry

In this project, we aim to analyze mental health survey data from technology workers in order to identify patterns and factors that contribute to mental health conditions. Our goal is to create machine learning models that can predict whether respondents currently have a mental health disorder, determine the factors that most affect mental health conditions in tech workers over time, and create a webpage to showcase our findings. We will be analyzing 6 years worth of survey data conducted from 2016 to 2021 by Open Sourcing Mental Illness (OSMI).









## Required Packages

All of the packages and libraries used in the project are documented in the requirements.txt file with the corresponding version.




## Data

The data is stored online on both OSMI's website and on kaggle. You must download each years raw survey data individually. Once you have downloaded all 6 datasets, please store them in the data folder after you have cloned the main repository (step 1 of Directions on Acquiring and Running the Code).

After the data has been stored correctly, proceed to start data wrangling using the "Data Cleaning Main".ipynb.
## Description of Directory

Below is a description of each of the files and folders in the root directory.

Folders:
- DSCI400Data: Contains each of the raw and updated csv files for the survey data

Files:
- DataCleaningMain.ipynb: Contains the code to wrangle and clean the data. This includes finding common questions between years, renaming inconsistent column titles, filtering out largely null columns, and combining all the datasets
- DataVectorization.ipynb: Contains the code to vectorize the combined dataframe from DataCleaningMain.




## Directions on Acquiring and Running the Code

1. Clone the main repository to a local server.
2. Install the Python packages and libraries in requirements.txt
3. Ensure that you can open and run Python files.
4. All of the python files contained under the root directory are the main files with code to open and run.
5. To run the code in the root directory, have the six data sets stored in the DSCI400Data folder
6. After completing steps 1 through 5, you should be able to open the python files and run through the code.