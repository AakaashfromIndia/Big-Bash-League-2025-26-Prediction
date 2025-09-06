<img width="1280" height="1280" alt="2" src="https://github.com/user-attachments/assets/c49042b0-eb46-4ff7-b6e7-86233dbd7d69" />

This repository contains machine learning models developed to predict the winners of matches in the Australian Big Bash League (BBL) and Women’s Big Bash League (WBBL). The models use detailed cricket match data, player statistics, and venue information to provide probabilistic predictions for upcoming matches.

Multiple Model Training - Trains and evaluates several supervised ML models:
 - Random Forest Classifier
 - Gradient Boosting Classifier
 - Logistic Regression
 - Support Vector Machine (SVM)
 - Neural Network (MLPClassifier)

An Ensemble Model combines multiple models (excluding neural net) into a VotingClassifier ensemble for robust predictions.

# Final predictions:

**1. Men's BBL**

| POS | TEAM                | Pld | W | L |
|-----|---------------------|-----|---|---|
| 1   | Sydney Sixers       | 10  | 9 | 1 |
| 2   | Hobart Hurricanes   | 10  | 8 | 2 |
| 3   | Perth Scorchers     | 10  | 7 | 3 |
| 4   | Brisbane Heat       | 10  | 6 | 4 |
| 5   | Sydney Thunder      | 10  | 4 | 6 |
| 6   | Melbourne Renegades | 10  | 3 | 7 |
| 7   | Adelaide Strikers   | 10  | 1 | 9 |
| 8   | Melbourne Stars     | 10  | 1 | 9 |

**2. Women's BBL**

| POS | TEAM                | Pld | W | L |
|-----|---------------------|-----|---|---|
| 1   | Sydney Sixers       | 10  | 8 | 2 |
| 2   | Perth Scorchers     | 10  | 8 | 2 |
| 3   | Adelaide Strikers   | 10  | 7 | 3 |
| 4   | Brisbane Heat       | 10  | 6 | 4 |
| 5   | Melbourne Renegades | 10  | 5 | 5 |
| 6   | Hobart Hurricanes   | 10  | 5 | 5 |
| 7   | Sydney Thunder      | 10  | 1 | 9 |
| 8   | Melbourne Stars     | 10  | 0 | 10 |

<img width="1280" height="1280" alt="8" src="https://github.com/user-attachments/assets/d912b14d-19cc-449d-9a21-98aa11a57139" />
<img width="1280" height="1280" alt="9" src="https://github.com/user-attachments/assets/65058e00-4f9c-4a83-a529-e42167a84cd9" />

