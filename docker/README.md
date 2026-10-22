# Docker

Build the image from the repository root so Docker can access the project
metadata and source files:

```powershell
docker build -f docker/Dockerfile -t python-project-template .
docker run --rm python-project-template
```

The image installs the application from `pyproject.toml` and starts the example
module. Add runtime dependencies to the project metadata so they are installed
when the image is built.
