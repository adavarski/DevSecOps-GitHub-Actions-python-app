## DevSecOps pipeline with Github Actions

<img src="pictures/DevSecOps-pipeline-GH-Actions-python-app.png?raw=true" width="1000">

Vulnerable app: https://owasp.org/www-project-pygoat/ -> PyGoat is written in python and used Django web framework as a platform. It has both traditional web application vulnerabilities (i.e. XSS, SQLi) as well.

SAST Scan -> static analysis of the application source code for exploits, bugs, vulnerabilites (Bandit)

Docker Image Scan - > Identify vulnerabilities in built images (DockerHub Scout Image Scanner)
