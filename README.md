# Node.js Docker CI/CD Demo

This project demonstrates a Node.js application containerized using Docker and automated using GitHub Actions CI/CD.

## Technologies Used

- Node.js
- Docker
- GitHub Actions
- GitHub
- JavaScript

## Project Structure

- `app.js` - Node.js application
- `Dockerfile` - Docker image configuration
- `package.json` - Project dependencies and scripts
- `.github/workflows/` - GitHub Actions CI/CD workflow

## Docker

Build the Docker image:

```bash
docker build -t nodejs-demo-app .
