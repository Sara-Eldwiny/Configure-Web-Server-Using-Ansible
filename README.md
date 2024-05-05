# Secure-Jenkins (ansible)

## Description:
SecureJenkins is a project aimed at setting up a secure and efficient Jenkins continuous integration and continuous deployment (CI/CD) environment. This project automates the installation and configuration of Java 17, Jenkins, and Nginx with SSL encryption, ensuring a robust and secure infrastructure for software development and deployment workflows.

## The installation process includes the following steps:

    Installing Java 17 using Amazon Corretto.
    Installing the latest version of Jenkins.
    Importing the Jenkins repository key for secure package installation.
    Starting the Jenkins service.
    Installing Nginx to act as a reverse proxy.
    Generating a self-signed SSL certificate for securing communication.
    Configuring Nginx to proxy requests to Jenkins with SSL encryption.
    Restarting Nginx to apply the configuration changes.

With SecureJenkins, organizations can quickly deploy a secure Jenkins environment, enabling streamlined development, testing, and deployment pipelines while prioritizing data integrity and confidentiality.
