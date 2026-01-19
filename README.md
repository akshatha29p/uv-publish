my-python-package
This Python package is built and published to JFrog Artifactory PyPI using GitHub Actions and uv.

Artifactory Upload URL
The GitHub Actions pipeline uses the following Artifactory endpoint for authentication and uploads:

https://${env:JFROG_USER}:${env:JFROG_PASS}@mill.jfrog.info:12176/artifactory/api/pypi/pypi-local
