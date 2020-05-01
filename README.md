# Docker container to run GitHub actions locally

Image for use with [act](https://github.com/nektos/act)

This docker image is based on the official node images, using Ubuntu rather
than Debian. The goal is to keep it trim and small, not to recreate the full
GitHub Actions environment.

## Installed packages

On top of the node `*-slim` docker steps, the following packages have been added:

- openssl

## Tested actions

- setup-python@v2
