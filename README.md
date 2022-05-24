# WeDukeCare Journaling Web App

📆 HackDuke 2021: Code for Good

🎯 Health and Wellness Track 

🔗 Main Repo: https://github.com/fool1280/mind-journal


## Google Cloud Platform Tech Stack 

- **App Engine and Cloud Build**

The web app is deployed on GCP's standard App Engine Platform as a highly-scalable application. Updates of the web application will be automatically deployed by Cloud Build. The new version will be automatically deployed through the trigger of an update on this specific repository and the old version will be kept (in case down-versioning is needed). Traffic to the web application is ensured to be divided evenly among all running nodes, downtime will be prevented.

- **Cloud Monitoring**

Uptime checks has been implemented for each deployment of the web application. Should there be a failure of deployment, an alerting policy has been created to alert the team through an email notification. Furthermore, a monitoring dashboard on the resources used on App Engine has been created. Budgets on CPU utilization, traffic load and storage has also been created.
