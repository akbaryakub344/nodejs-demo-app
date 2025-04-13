# Node.js Demo App with CI/CD

This is my internship project. It’s a small webpage with automation.

## What It Does
- Shows “Hello from Node.js Demo App!” when someone visits it.
- Automatically packs and shares the webpage when I change the code.

## My Files
- `index.js`: Makes the webpage.
- `package.json`: Lists tools the webpage needs.
- `Dockerfile`: Tells Docker how to pack the webpage.
- `.dockerignore`: Skips extra files.
- `.github/workflows/main.yml`: Runs the automation.

## Automation
- Starts when I update my code.
- Checks the webpage, packs it, and sends it to DockerHub.
- The packed webpage is at `yourakbaryakub123/nodejs-demo-app:latest`.

## Internship Task
This finishes Task 1: Automate Code Deployment Using CI/CD Pipeline.
