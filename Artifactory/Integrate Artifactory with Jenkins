Integrate Artifactory with Jenkins
pre-requisites
An Artifactory server 
A Jenkins Server 
Integration Steps
Login to Jenkins to integrate Artifactory with Jenkins

Install "Artifactory" plug-in
Manage Jenkins -> Jenkins Plugins -> available -> artifactory
Configure Artifactory server credentials
Manage Jenkins -> Configure System -> Artifactory
Artifactory Servers
Server ID : Artifactory-Server
URL : Artifactory Server URL
Username : admin
Password : `admin@123
Create a Freestyle Project
Create a new job
Job Name : artifactory-project
Source code management
Git URL : get URL here
Build Environment
Maven3-Artifactory Integration : `<provide Artifactory server and repository details
`

Build --> Invoke Artifactory Maven3
- Goals: clean install
Execute job
Create a Maven Project
Create a new job
Job Name : artifactory-project
Source code management
Git URL : get URL here
Build Environment
Resolve artifacts from Artifactory : <provide Artifactory server and repository details>
Build - Goals: clean install
Post-build Actions
Deploy Artifacts to Artifactory : <provide Artifactory server and repository details>
Execute job
