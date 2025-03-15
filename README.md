# Docker Web App
A simple project to practice Docker by containerizing a static HTML webpage.

## How to Run
1. Clone this repository.
2. Run `docker build -t my-web-app .` to build the image.
3. Run `docker run -d -p 8080:80 my-web-app` to start the container.
4. Open `http://localhost:8080` in your browser.

## Purpose
This project was created as part of my self-study in DevOps to learn containerization with Docker.
