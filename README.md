## DevSecOps pipeline with Github Actions

<img src="pictures/DevSecOps-pipeline-GH-Actions-python-app.png?raw=true" width="1000">

OWASP vulnerable Python app: https://github.com/adeyosemanputra/pygoat -> PyGoat is written in python and used Django web framework as a platform. It has both traditional web application vulnerabilities (i.e. XSS, SQLi) as well. Ref: https://owasp.org/www-project-pygoat/

SAST Scan with Bandit -> static analysis of the application source code for exploits, bugs, vulnerabilites (Bandit)

Container Image Scanning with Docker Scout - > Identify vulnerabilities in built images (DockerHub Scout Image Scanner)

How to generate scan reports

Ref: Docker Scout Links:
- Docker Scout: https://docs.docker.com/scout/
- Docker Scout CLI: https://docs.docker.com/engine/refere...](https://docs.docker.com/engine/reference/commandline/scout/
- Docker Scout GitHub Action: https://github.com/docker/scout-action


