# DevOps CI/CD Project (Docker + Jenkins + AWS)

## About This Project

This is a basic DevOps project that I created to understand how real-world application deployment works using DevOps tools.

In this project, I have taken a simple Python Flask application and deployed it using Docker. I also created a basic CI/CD pipeline using Jenkins to automate the process.

The main goal of this project was to get hands-on experience with tools like Docker, Jenkins, and AWS.

## Tools & Technologies Used

* Python (Flask)
* Docker
* Jenkins
* GitHub
* AWS EC2 (for deployment)


## What I Did in This Project

* Created a simple Flask web application
* Uploaded the code to GitHub
* Wrote a Dockerfile to containerize the app
* Built and ran the Docker container
* Created a Jenkins pipeline to automate build and run process
* Deployed the application on AWS EC2

## How to Run This Project

### 1. Clone the repository

git clone https://github.com/YOUR_USERNAME/devops-ci-cd-docker-aws-project.git

cd devops-ci-cd-docker-aws-project

### 2. Build Docker image

docker build -t devops-app .

### 3. Run container

docker run -d -p 5000:5000 devops-app

### 4. Open in browser

http://localhost:5000


## Jenkins Pipeline (Basic Idea)

In Jenkins, I created a pipeline that:

* Pulls code from GitHub
* Builds Docker image
* Runs the container

This helped me understand how CI/CD works in a simple way.

## What I Learned

* Basic understanding of DevOps workflow
* How Docker works and how to create containers
* How Jenkins pipeline automates tasks
* Basic idea of deploying on AWS EC2

## Note

This is a beginner-level project created for learning purpose.


