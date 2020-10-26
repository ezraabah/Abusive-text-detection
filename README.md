# Abusive-text-detection
### 1. Problem Definition
The objective of this project is to develop and evaluate abusive language detection models for the given dataset. To do this, this project sets off in section 2. by importing, exploring and cleaning the data. In section 3, the data is preprocessed for modelling. The modelling section, section 4, starts by creating a baseline model afterwhich subsequent models are trained, varying hyperparameters. Finally in section 5, the trained models are evaluated using accuracy, precision, F-1 score and Recall and the optimum hyperparameter is selected.

### 2. Data Set
#### 2.1 About Data
This dataset, "agr_en_train.csv" is a Comma Separated Variable (.csv) file which contains about 12,000 observations and 3 columns namely: unique_id,text and aggression-level.

text: The text column contains texts collected from social media.
aggression-level: This measures the level of aggression in the text. There are three aggression levels:
'Overtly Aggressive’ denoted as OAG
‘Covertly Aggressive’ denoted as CAG
‘Non-aggressive’ denoted as NAG
The full dataset (both the train and test sets) is licensed under Creative Commons Non-Commercial Share-Alike 4.0 licence CC-BY-NC-SA 4.0
