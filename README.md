# PostmanProject
Paylocity benefits

This repo contains a Postman project which has some endpoints and scripts to test Employee benefits API behavior.

# Details
# URL and Login info:

URL: https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Account/Login

Your username, password, and auth token for API testing will be provided to you in a
separate email.

# API Documentation:
The API documentation can be found at the below link:
https://documenter.getpostman.com/view/2314100/SWTEbbi6
Note that you will need to use your assigned auth token in the header of your requests
in order to access the API.
For example: Key: Authorization; Value: Basic <authToken>

Postman users can use the “Run in Postman” button to migrate the requests to their
Postman account. If you prefer Swagger documentation, you can find it

here: https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/swagger/v1/swagger.json

# The Application:
One of the critical functions that we provide for our clients is the ability to pay for their
employees’ benefits packages. A portion of these costs are deducted from their
paycheck, and we handle that deduction. This is a small, buggy, sample application
that allows the user (an employer) to add, edit, and delete employees and their dependents.

# Assumptions:
  • All employees are paid $2000 per paycheck before deductions
  • There are 26 paychecks in a year
  • The cost of benefits is $1000/year for each employee
  • Each dependent incurs a cost of $500/year
