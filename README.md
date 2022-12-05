# DeusCraft_technical_task

Technical task from DeusCraft

## Description of the files

Taks contains two working files:
  - Deuscraft_metrics - Analysis of product metrics
  - Deuscraft A/B testing - Conducting A/B testing

### Deuscraft_metrics task description

Using the [data](https://docs.google.com/spreadsheets/d/1UX57qWCJun9nHnyTaj4jPlSez3No9pUF9pO9wMosIaw/edit#gid=0), calculate and plot the metrics (create
a copy of the document, save the formulas, attach a link to the document with the answer).
  
Analyze the received data. What places are worth paying attention to? List metrics:
  - ARPU - average revenue per player
  - ARPPU - average revenue per payer
  - Paying Share - share of paying
  - Retention Day 1 - retention of the th day
  -  Retention Day 7 - retention of the 7th day
  -  Retention Day 28 - retention of the 8th day
  
### Deuscraft A/B testing task description

We have conducted A/B testing for our game. Each player was assigned to one of the groups (control or test) and received an identifier of 0 or 1, respectively. In the test, we wanted to test the hypothesis that changes in the test group will positively affect monetary indicators: ARPU, ARPPU and conversion. Run an A/B test. Please use the provided csv file. The data contains the following fields:
  - geo_country - player's country
  - test_timestamp - date when the player entered the test
  - user_revenue - revenue per player
  - user_payments - number of player payments
  - user_id - player ID
  - test_group - test group ID
