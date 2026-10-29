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

