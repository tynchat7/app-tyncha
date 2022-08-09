# Documentation for "Barter" app
## Requirments

- Based: Django
- Language: Python3
---
## Steps to use the app 
---

- You will need to clone the repo
```
- git clone git@github.com:fuchicorp/apps.git
- Choose "barter" application 
- Create your own PRIVATE repo on your github account
- Copy "barter" application folder from app repo to your repo.
```
---
## Steps to run the app in local
---
- Install the libraries
```
python3 -m pip install -r requirements.txt
```

- Run the app
```
python3 main/apps.py
```

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


