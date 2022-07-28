# Q&A Automation Challenge

## Purpose and objective

Skills Workflow, as an organization, must make sure we hire resources that are not only knowledgeable but resourceful as well.
Here we propose a challenge to candidates for positions that involve Q&A and Q&A Automation.

The main goal of this challenge is to assess the candidate's knowledge when it comes to the use of Automation Tools in the Q&A process, 
including all main concepts about Q&A, possible integration with CI/CD tools, etc.
It will be relevant to assess how the candidate can think out of the box when presenting the solution.

## Scope

* To address this challenge candidates can select a framework of choice, it is advised to use open source solutions.
* Any doubts or assumptions regarding the challenge must be documented to be discussed later
* Assume that you are a Q&A Automation Tester producing: a Test plan with multiple test cases for a WebApp in Angular.

## The challenge
 
The challenge consists of producing a Test Plan with UI tests over an Angular WebApp.

Starting point should be the application in the url:

https://playground-dev-we.skillsworkflow.com/login

For login purposes use the following credentials:
* User: QA Tester
* Password: 12345

Test cases should verify these behaviours:

1. Login with invalid credentials
2. Login with valid credentials should navigate to homepage
3. Login and and test navigation access to Clients list
4. Login, navigate to Client List and access first available Client
5. Login and Logout operation

It is up to the candidate to design and implement using tools/frameworks of choice and document test results the best way he can.

### Output
The result of this challenge should be:
1. Script with the Test Plan definition and run routine
2. Include an execution report with evidences taken from an execution.
3. Document how this could be incorporated in a CI/CD pipeline with Azure DevOps. 

**Important**

> Available code/tests/scripts should be made available on a github repository so we can evaluate.
>
> Don't forget to include eventual design decisions or assumptions on the repo README file.
