# Bogoslovtcev Eduard UI Garden

This project is a React + TypeScript component library built with Create React App and Storybook.

The application is containerized using Docker and runs a production build served by Nginx.

---

## Requirements

- Docker installed
- Node.js 20+ (only needed if running locally without Docker)

---

## Build Docker Image

From the root of the project, run:

docker build -t bogoslovtcev_ui_garden2 .

---

## Run Docker Container

docker run -d -p 8018:80 --name Bogoslovtcev_Eduard_coding_assignment13 bogoslovtcev_ui_garden2

---

## Open in Browser

http://localhost:8018

---

## Stop Container

docker stop Bogoslovtcev_Eduard_coding_assignment13

---

## Remove Container

docker rm Bogoslovtcev_Eduard_coding_assignment13

---

## Remove Image

docker rmi bogoslovtcev_ui_garden2
