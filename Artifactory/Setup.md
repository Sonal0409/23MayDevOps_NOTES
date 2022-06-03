Artifacotry Setup
An artifact repository manages your end-to-end artifact lifecycle and supports different software package management systems while providing consistency to your CI/CD workflow. An artifact repository is both a source for artifacts needed for a build and a target to deploy artifacts generated in the build process.

JFrog Artifactory is a universal DevOps solution providing end-to-end automation and management of binaries and artifacts through the application delivery process that improves productivity across your development ecosystem. It enables freedom of choice supporting 25+ software build packages, all major CI/CD platforms, and DevOps tools you already use.

Pre-requisites:
An AWS T2.small EC2 instance (Linux)
Open port 8081 and 8082 in the security group
Installation Steps
Login to instance as a root user and install Java

 yum install java-1.8* -y 
Download Artifactory packages onto /opt/
For Latest version of Artifactory OSS download it from here
For Older version of Artifactory OSS download it from here
For Latest version of Artifactory Pro download it from here

cd /opt 
wget https://jfrog.bintray.com/artifactory/jfrog-artifactory-oss-6.9.6.zip
extract artifactory tar.gz file

unzip jfrog-artifactory-oss-6.9.6.zip
Go inside to bin directory and start the services

cd /opt/jfrog-artifactory-oss-6.9.6/bin
./artifactory.sh start
access artifactory from browser

http://<PUBLIC_IP_Address>:8081 
Provide credentials

username: admin
password: passwrod 
Not able to start Artifactory services?
Make sure You meet the Artifacrtory system requirements.
