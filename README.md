#                                                         NBA Draft Assistant

Team Members : AKSHAY GUPTA

## Predicting if a NBA draft candidate would be successful in the NBA
Based on the performance of a player in college, this model will predict whether or not a player would be successful in the NBA.
In precise terms, a player is successful in the NBA if he achieves one of the following

 - NBA All Star
 - All NBA Team
 - All Defensive Team
 - NBA Most Valueable Player
 - Defensive Player of the year
 - NBA Sixth Man of the year
 
## Data Source
There was no pre-existing data for this purpose, so the dataset was built by scraping three different websites and merging the pulled data.
.<br>
<a href="https://github.com/akshaygupta16/sportsense/blob/master/ScoutingModelv3.ipynb">Click here to open the notebook created for building the dataset</a>
<br>


## This project Applies the CRISP-DM Process

### Domain Knowledge
Data is big and continuously growing when it comes to sports and it has started affecting the different verticals of sports in astonishing ways. Front offices and coaches face a lot of challenges in decision making (predictions), and leveraging data analytics makes this task much more frutitious.

### Data Understanding & EDA
The data being dealt over here consists the information and college games statistics of the players currently in the NBA (selected through the NBA draft). The notebook contains some patterns that uncover the things successful NBA players did during their college career.

### Data Preprocessing
The dataset consists of a lot of null values that have majorly been taken care of using imputation techniques like KNN imputation etc.
Not to mention the scaling that was needed to be done.

### Modelling
The aim of this project is to come up with a classification model with the parameter "NBA Success?" that has values "yes" or "no" as the target variable. Different modeling techniques like logistic regression, decision trees and Random forest have been applied.

### Evaluation
The accuracy scores of all the models applied are compared to find out that logictic regression performs best.

### Conclusion
Given the college statisitcs of a player and the position he played on the team (Forward/Center/Guard), this model predicts wether or not the player would be successful in the NBA with an accuracy of 0.92
