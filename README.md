# Dmoney-Api-Jmx

## Tools and technology used
  - Jmeter

## Scenario
Create a jmx file from this collection
https://www.getpostman.com/collections/a8f908e0ee1d77cb6f85

Add following requests:
  - Login to user.
  - Get user list.
  - Create a user.
  - Search the newly created user by id.
  - Search the newly created user by phone number.
  - Search the newly created user by email.
  - Update the user phone number.
  - Delete the user.
 
## How to run this project
- clone this repository.
- put the jmx file the bin folder of the jmeter installation path.
- open cmd and hit the following command
```jmeter```
- from jmeter open the file from the bin and hit the run button.

## For Report Generation
- open cmd from the bin folder of the jmeter installation path. and hit the following command
- ```jmeter -n -t Dmoney-API.jmx -l Dmoney-API.csv -e -o Reports```

 ## Prerequisite
 - Jmeter must be installed
 
 ## Output
 ## Load Test Report
 ![load test report](https://user-images.githubusercontent.com/76776200/195670109-867771dc-8ca1-4920-a56c-77e775c0c898.png)

