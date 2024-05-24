# Data 641 Final Project -- Predicting Neuroticism from Social Media Posts
Authors: Iris Yu, Lydia Yoder, Diane Sun, Anna Lavrentieva

## root 
- writeup.pdf is our writeup 

## presentation Folder
- contains out presentation slides as both .pdf and .pptx files for convenience 

## code_data Folder
To recreate our project: 
This directory already contains the 'cleaned' version of the myPersonality data as 'group.csv'
(Unfortunately the code is not modularized, this project is for exploratory purposes only and is not meant to be deployed at an industrial level) <3 
### Cleaning
-- ideally, should not try to recreate this due to variation in results each time lang detect and jamspell is run
1. Read 'wcpr_mypersonality.csv' file into 'languagedetect.ipynb'
2. Manually sort through language classifications to make sure only english remains
3. Read results into 'jamspell.ipynb'
4. Read output into 'clean' -- final output is already saved as 'group.csv'
    - this directory contains our custom slang dictionary 'slang.txt'

### Classification
-- read in 'group.csv' as data source
1. Baseline models are located in 'basemodels.ipynb'
2. BERT and XLNet are in 'bertxlnet.ipynb'