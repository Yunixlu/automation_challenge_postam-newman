# Automation-challenge_Postam-Newman

**Welcome**

### Structure 
- **backEnd**
- Collection: 
The folder contains a file .json with the requests and tests

- envVariables: 
The folder contains a file .json with the variables of QA environment 

- DDT: 
This folder contains the files the collection, environment and file .csv to run the request and create several tasks, also a file with the report of the execution.

- Reports: 
The folder contains the report.html that is automatically generated with Newman.
Also a folder with the report of the tests without CLI generated from Postman

- **Bonus.txt:**
The file contains the answer to point 1 on bonus section



### Run the project

- Run all tests and create a report: 
`$ npm run testAPI`


#### Note:
- This project was develop on macOS Catalina, version 10.15.6
- Node version 10.13.0
- Npm version 6.10.3
- Newman: ^5.2.2
- Newman-reporter-htmlextra: ^1.20.1

