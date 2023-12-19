# Python-Assignment

The code explains the requirement for setting up country codes to speed up processing of expense reports by creating a simple cli.
A code in python is wriiten which shows  a country lookup service.
This code works at the following API https://www.travel-advisory.info/api.
Here the code has been converteded in Craft demo to a REST service with two routes.
The output shows health returns health of your service via /health and /convert – converts country name to country code.
Also,/diag check returns status of the api https://www.travel-advisory.info/api return {"api_status":{... "code":200,"status":"ok"} that you obtained from hitting an API.
A dockerfile is created to containerise the application on local k8s cluster on your workstation and deployed on it.
