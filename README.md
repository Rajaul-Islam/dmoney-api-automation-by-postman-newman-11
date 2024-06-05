
# dmoney-api-automation by postman & newman

## About this project:
### This is A Simple API Testing Projectd where i try to D-money which is a demo financial related project where fake money can be transferred. In this project I have automate the d-money api using postman and newman. Here I have covered folowing.

## Tools & Technology used:
- postman
- newman
- newman-html-extra

## Prerequisites
- nodejs
  
## How to run this project:
- clone this project
- Then run the follwing command:
- ``` npm i ```
- ``` npm test ```
- add the env file(on request)

## Test case
- https://docs.google.com/spreadsheets/d/1Cy32ygK2AF_dhE2NjlLk4_qKHDTFjuorN_IRq5oblLc/edit?usp=sharing
## Bug Report
- https://docs.google.com/spreadsheets/d/1Km-PmmRyOQA6TA2moEafreRc_uH-tyFVymFEspORhys/edit?usp=sharing
## d-money API documentation
- https://documenter.getpostman.com/view/22666982/2sA3Qv9WYo

## Test Report


## Newman Full Live Report Link


## Positive and Negative case are Created for Follwing Scenraio.

1. Admin creates an agent and random 2 customers. Admin email: admin@roadtocareer.net/ Pass: 1234
2. Deposit some money from SYSTEM account to the agent. System account: SYSTEM (range 10 tk to 10000 tk)
3. Agent deposit to any of 1 customer
4. Check agent balance
5. Then withdraw any amount by the customer from the agent (range 10 tk to 10000 tk)
6. Then the customer checks balance
7. Then send money to the other customer
8. Then from the another customer payment to any merchant (create a merchant account)
9. Then the second customer will check both balance and statement
10. Then the merchant will check his own balance
