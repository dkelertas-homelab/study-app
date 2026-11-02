# DevOps Study App Backend

# Initialise the project
uv init --package backend

# Install the package
uv sync --locked --no-editable

# Add dependancies
uv add fastapi
uv add httpx
uv add uvicorn

# Run

uv run study-tracker-api


uv sync --locked --no-editable
uv run study-tracker-api
v Dockerfile
TAG=00 && docker build -t backend:$TAG
docker image ls
docker run backend:00

TAG=00 && trivy image --format table --severity CRITICAL,HIGH backend:$TAG

Check out chainguard.dev images - paid free from CVE docker images

TAG=02 && trivy image --format table --ignore-unfixed --severity CRITICAL,HIGH backend:$TAG
