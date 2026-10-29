# DevOps Study App Frontend

# Initialise the project
uv init --package frontend

# Install the package
uv sync --locked --no-editable

# Add dependancies
uv add flask
uv add requests

# Run

uv run study-tracker-frontend

