# cloudproject1

Here is the high level overview of the process:

1) Create a github repository
2) Create a corresponding GCP Project
3) Establish a communication channel between these two via SSH Keys
4) Using one of the sample Github repository files(python-docs-sample), created required files that can be updated via the cloud shell workspace
5) Leveraged the existing code and updated as required into these files that I have created in Step # 4
6) Installed all the packages and made sure the latest version of python is in place. 
7) A virtual environment is now created
8) Created an application engine
9) Ran a local flask server and tested in real time when I made changes to the main.py code
10) Deployed the application to Google Cloud Storage and now it is available on public url
11) Set up continous deployment (Cloudbuild.yaml). 
12) Automate the cloud build API's, Grant app engine access
13) Updated Cloud build.yaml with a code and commited it to a repository
14) Pushed all the pertinent files to github
15) Enabled Build Trigger to sync. any changes to github.
16) Validated the flow by changing the route call and associated trigger history 
