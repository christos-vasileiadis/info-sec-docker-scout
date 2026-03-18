# InfoSec Docker Scout

This repository contains a simple DevSecOps pipeline created for an Information Systems Security course assignment.

The pipeline:
- builds a Docker image from the project files,
- pushes the image to GitHub Container Registry (`ghcr.io`),
- scans the image for known vulnerabilities using Docker Scout through GitHub Actions.
