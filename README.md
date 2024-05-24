# Data 641 Final Project -- Predicting Neuroticism from Social Media Posts
Authors: Iris Yu, Lydia Yoder, Diane Sun, Anna Lavrentieva
- The data used for this project is privately owned and cannot be posted for the sake of privacy
- The original dataset consisted of social media posts gathered from 250 unique users
## root 
- writeup.pdf is our writeup that contains the result of our exploration


## code
To recreate our project: 
This directory already contains the 'cleaned' version of the myPersonality data as 'group.csv'
(Unfortunately the code is not modularized, this project is for exploratory purposes only)
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
