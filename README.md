
# Automated CI Pipeline Using GitHub Actions and Docker

## 1. Project Overview
This project demonstrates Continuous Integration (CI) for a
Python Flask web application using GitHub Actions and Docker.

## 2. Objectives
- Develop a simple Flask web application.
- Write automated tests using pytest.
- Configure a GitHub Actions workflow.
- Automatically run tests when code is pushed or a pull
  request is opened.
- Build a Docker image in the CI environment.

## 3. Technologies Used
- Python 3.12
- Flask
- pytest
- Git and GitHub
- GitHub Actions
- Docker

## 4. Application Features
- Home endpoint: /
- Health-check endpoint: /health
- Automated endpoint tests

## 5. CI Workflow
1. A developer pushes code to GitHub.
2. GitHub Actions checks out the repository.
3. Python is configured on an Ubuntu runner.
4. Dependencies are installed.
5. Automated tests are executed.
6. Docker builds an image of the application.

## 6. Testing and Results
The application contains two automated tests covering the
home endpoint and health-check endpoint.

The GitHub Actions workflow completed successfully, with
both tests passing and the Docker image building successfully.

## 7. Limitations
The project builds a Docker image but does not publish it
to a container registry or deploy the application.

## 8. Future Enhancements
- Publish the image to Docker Hub or GitHub Container Registry.
- Add security and dependency scanning.
- Deploy the application to a cloud platform.
- Add monitoring and logging.

## 9. Conclusion
This project demonstrates a basic automated CI pipeline
integrating Python testing, GitHub Actions, and Docker
container image building.
