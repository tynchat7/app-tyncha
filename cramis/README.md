# Documentation for "cramis" app
## Requirments

- Based: Dotnet .Net
- Language: C#
---
## Steps to use the app 
---
- You will need to clone the repo
```
- git clone git@github.com:fuchicorp/apps.git
- Choose "cramis" application 
- Create your own PRIVATE repo on your github account
- Copy "cramis" application folder from app repo to your repo.
```
---
## Steps to run the app in local
---
## DevOpsLeadsApi
Simple Leads Api for our DevOps Practicum

## Getting Started
This project was developed using .Net Core version `3.1.201`

To build the project, run the command: `dotnet build`

To run the project's tests, run the command: `dotnet test`

To run the full project, run the command `dotnet run --project DevOpsLeadsApi.Api/`

Note: Each of the above commands will restore tha projects package dependencies.



## Endpoints
| Path              | Method   | Request  |
| ----------------- | -------- | -------- |
| `/api/leads`      | `GET`    |          |
| `/api/leads/{id}` | `GET`    |          |
| `/api/leads`      | `POST`   | Lead Obj |
| `/api/leads/{id}` | `PUT`    | Lead Obj |
| `/api/leads/{id}` | `DELETE` |          |
---
## Steps to proceed to Ticket-5
---
- Dockerize the files in that folder. Build and test that docker image
- Create a helm chart to deploy your application.
- Deploy and ensure it works correctly and
   you can view the image at the URL you specified.
- Create a terraform module and ensure the helm chart is soft coded.
- Use the groovy files from hello-world to help create pipelines and deploy your application with your Jenkins.
- Deploy your application with Jenkins to all environments (DEV, QA, STAGE and PROD). 
- Once this is complete, provide your URLs to your application in your ticket for instructors to check.
---


