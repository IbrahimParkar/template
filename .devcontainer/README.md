# Development container

Open this repository in Visual Studio Code with the Dev Containers extension,
then run **Dev Containers: Reopen in Container** from the Command Palette. The
container uses Python 3.13, installs `uv`, and runs `uv sync` after creation.

After setup, the commands in the root [README](../README.md) are available in
the container. If you change the Python version in `.python-version`, update
the image tag in `devcontainer.json` to keep the environments aligned.
