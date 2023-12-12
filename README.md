## DevSecOps pipeline/workflow with Github Actions

Overview: 

<img src="pictures/DevSecOps-pipeline-GH-Actions-python-app.png?raw=true" width="1000">

### OWASP vulnerable Python app: 

https://github.com/adeyosemanputra/pygoat -> PyGoat is written in python and used Django web framework as a platform. It has both traditional web application vulnerabilities (i.e. XSS, SQLi) as well. 

Ref: https://owasp.org/www-project-pygoat/

### SAST Scan with Bandit:
SAST (Static Application Security Testing): static analysis of the application source code for exploits, bugs, vulnerabilites -> Bandit (Bandit is a tool designed to find common security issues in Python code)

Ref: Bandit 
- https://bandit.readthedocs.io/en/latest/
- https://github.com/PyCQA/bandit

### Container Image Scanning with Docker Scout:
Identify vulnerabilities in built images -> DockerHub Scout Image Scanner

Note: Docker Scout is available through multiple interfaces, including the Docker Desktop and DockerHub user interfaces, as well as a web-based user interface and a command-line interface (CLI) plugin.
This is a demo about the integration of Docker Scout with GitHub actions using the CLI.

Ref: Docker Scout Links:
- Docker Scout: https://docs.docker.com/scout/
- Docker Scout CLI: https://docs.docker.com/engine/reference/commandline/scout/ && https://github.com/docker/scout-cli
- Docker Scout GitHub Action: https://github.com/docker/scout-action

Note: We can use Snyk instead of Bandit & Scout (Bitbucket use Snyk)

Ref: Snyk:
- https://snyk.io/partners/docker/
- https://github.com/snyk/actions
  
### How to generate scan reports (Bandit & Docker Scout)

### How to analyze scan reports (json report files)

Ref: 
https://www.defectdojo.org


### GH Actions References: 

List of GitHub Actions:

https://github.com/actions
https://github.com/marketplace?type=actions

Events:

https://docs.github.com/en/free-pro-team@latest/actions/reference/events-that-trigger-workflows

GH actions we use in this repo:

https://github.com/docker/scout-action
...
