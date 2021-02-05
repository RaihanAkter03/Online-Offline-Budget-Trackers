# Online-Offline-Budget-Trackers

GitHub Repository URL : https://github.com/RaihanAkter03/Online-Offline-Budget-Trackers

Deplyed App URL : https://glacial-cove-35524.herokuapp.com/

![GNU License](https://img.shields.io/badge/license-GNU-green)

## Description 

* The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline shows online 

  * Enter expenses offline shows online

When brought back online:

  * Offline entries will be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.


## Technical
  * Frist we have to install npm dependency.
  * Application uses mongo db and index db for offline
  * under public folder create db.js file to add database codes.
  * we have to add a gitignore file.
  * A service worker and manifest file have to add.
  * Deployed the code on heroku. before that we have to create database on mongoDB.

* Deployed application screenshot given below 


![application](budget1.PNG)
![application](budget2.PNG)