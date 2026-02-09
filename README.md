# DevOps Demo App 🚀

A professional Flask application designed to demonstrate a full DevOps lifecycle.

## Features
- **Modern Backend:** Python 3.12 + Flask.
- **CI/CD Ready:** Automated testing and building with GitHub Actions.
- **Containerized:** Ready to run anywhere with Docker.

## App Endpoints
- `GET /` -> Returns a "Hello DevOps" message.
- `GET /health` -> Health check endpoint for monitoring (returns JSON).

## How to Run

### 1. Using Docker (Recommended)
Build and run without installing Python locally:
```bash
# Build the image
docker build -t devops-app .

# Run the container
docker run -d -p 5000:5000 --name my-app devops-app
