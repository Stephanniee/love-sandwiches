# Love Sandwiches Data Automation Project
Welcome to the Love Sandwiches Data Automation Project! Is a command-line-based Python program designed to handle data automation for a fictional sandwich company.

## Index 
* [Overview](#overview)
* [Objective](#objective)
* [Structure](#structure)
* [Deployment](#deployment)
* [Constraints](#constraints)
* [Credits](#credits)

## Overview
Love Sandwiches operates a local market stall where they sell a small range of sandwiches. Each market day, their staff prepares stock to sell. If they sell out of a particular sandwich, they make extra for their customers. Any unsold sandwiches are discarded at the end of the day.
To develop a Python program that:
1.	Collect the company's market day sales data.
2.	Calculate the surplus sandwiches for the day.
3.	Produce recommendations for the number of each sandwich to make for the next market.
The primary goal of this project is to save the company's staff time by automating a repetitive task and to help reduce surplus by better predicting sales for future markets.

## Objectives
1.	Collect market day sales data.
2.	Calculate surplus sandwiches.
3.	Generate recommendations for future market stock based on sales data.
4.	Interact with a Google Sheet to push and pull data.

## Structure 
![program structure](https://github.com/Stephanniee/love-sandwiches/assets/140328398/281da448-423e-4f43-87a9-e9c4424906a0)

## Deployment 
1.	Heroku App Creation: Created a new Heroku app with a unique name, specifying the desired region.
3.	Configuring Environment Variables: Added necessary environment variables, such as sensitive data or credentials, in the config vars section to ensure secure application operation.
4.	Adding Buildpacks: Installed additional dependencies essential for the application through buildpacks, including Python and Node.js.
5.	Selecting Deployment Method: Chose the preferred deployment method for the application.
6.	Connecting to GitHub: Selected GitHub as the deployment source and established a connection between the Heroku app and the GitHub repository, specifically linking to the repository named "love-sandwiches".
9.	Manual Deployment: Deployed the application manually to ensure control over the deployment process.
10.	Viewing Deployment Logs: Reviewed the deployment logs to monitor the deployment progress and any potential issues.
8.	Successful Deployment Confirmation: Confirmed the successful deployment of the application with the message "App was successfully deployed".

Following these steps, the Love Sandwiches Data Automation Project was effectively deployed on Heroku, equipped to streamline tasks and enhance operational efficiency for the fictional sandwich company.

## Constraints
The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.

## Credits 
Code Institute 
