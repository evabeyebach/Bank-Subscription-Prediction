# Bank-Subscription-Prediction
The objective of this case study was to develop and compare models to predict client subscription (yes or no) to term deposits of a Portuguese bank.

## Introduction
The case study aimed to develop Logistic Regression and Linear Discriminant Analysis (LDA) models to predict client subscription to term deposits from data of a Portuguese bank's marketing campaign. The objective was to determine which model provides superior predictive accuracy and to identify key influencing variables.
Our goal was to pinpoint the optimal model and predictor variables for identifying potential customers likely to subscribe to a term deposit. Achieving this would allow us to more effectively allocate the firm's resources toward prospective customers, optimizing call efforts and targeting strategies. 

## Data

- age (numeric)
- job : type of job
- marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means
divorced or widowed)
- education (categorical:
'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unkn
own’)
- default: has credit in default? (categorical: 'no','yes','unknown’)
- housing: has housing loan? (categorical: 'no','yes','unknown’)
- loan: has personal loan? (categorical: 'no','yes','unknown')

- contact: contact communication type (categorical: 'cellular','telephone’)
- month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec’)
- day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri’)
- duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects
Other attributes:
- campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
- pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
- previous: number of contacts performed before this campaign and for this client (numeric)
- poutcome: outcome of the previous marketing campaign (categorical:
'failure','nonexistent','success’)
