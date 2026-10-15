# Cloud CI/CD Pipeline Using Jenkins

## Objective
To implement a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins, Docker, GitHub, and Flask.

## Technologies Used
- Python and Flask
- Git and GitHub
- Jenkins
- Docker
- AWS EC2 (Ubuntu)

## Application
This project contains a simple Flask web application that runs on port 5000.

## Project Files
- `app.py` - Flask application
- `requirements.txt` - Python dependencies
- `Dockerfile` - Instructions to build the Docker image
- `Jenkinsfile` - Jenkins pipeline configuration (to be added)

## CI/CD Workflow
1. Push application code to GitHub.
2. Jenkins retrieves the source code.
3. Jenkins builds a Docker image.
4. Jenkins deploys the application in a Docker container.
5. Access the running application through the browser.

## Application Output
CI/CD Pipeline Version 1
