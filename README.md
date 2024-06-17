**Project Overview**

This project involved utilizing Vagrant, Ansible, Docker, and Jenkins. Here's the exercise we were tasked with:

**Getting Started**

1) Provision a Rocky Linux 9 VM: We'll use Vagrant to create a virtual machine running Rocky Linux 9.
   
2) Automate Docker Installation with Ansible: Ansible will automate the installation of Docker on the provisioned VM.

3) Install Jenkins (Master only) using Docker-based Ansible: Ansible will leverage Docker to install Jenkins on the designated master node.
   
4) Develop a Flask Dockerfile Application: Create a Dockerfile that builds a Python Flask application printing "Hello World".

5) Create a Jenkins Pipeline (flask-app-example-build): Define a declarative pipeline in Jenkins that utilizes a Docker image to build and push the application to your DockerHub account. The Docker image tag should follow these conventions:

git tag: Use the same tag as the Git tag for builds triggered from a Git tag.

master branch: Use "latest" for builds triggered from the main branch.

develop branch: Use "develop + <commit SHA>" for builds triggered from the develop branch, where <commit SHA> represents the latest commit hash.
