Dockerized Getting Started App
Project Overview

This project demonstrates how to containerize an existing web application using Docker.

The original application code was cloned from the Docker Getting Started repository. My contribution was to package the application into a Docker container, build the Docker image, and successfully run the application locally.

What I Did
Cloned the existing application source code.
Created a Dockerfile for the application.
Built a Docker image using Docker.
Ran the container locally.
Verified that the application was accessible through the browser on localhost.
Technologies Used
Docker
Dockerfile
Node.js (or the application's runtime)
Git
GitHub
Commands Used

Clone the repository:

git clone <original-repository-url>

Build the Docker image:

docker build -t getting-started-app .

Run the container:

docker run -dp 3000:3000 getting-started-app

Accessed the application at:

http://localhost:3000
Learning Outcomes

Through this project I learned how to:

Create a Dockerfile.
Build Docker images.
Run and manage Docker containers.
Expose application ports.
Verify a containerized application on a local machine.

Note : The application source code belongs to its original authors. This repository focuses on demonstrating the Docker containerization process rather than the development of the application itself.
