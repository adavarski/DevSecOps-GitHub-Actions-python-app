## DevSecOps pipeline with Github Actions

Overview: 

<img src="pictures/DevSecOps-pipeline-GH-Actions-python-app.png?raw=true" width="1000">

### OWASP vulnerable Python app: 

https://github.com/adeyosemanputra/pygoat -> PyGoat is written in python and used Django web framework as a platform. It has both traditional web application vulnerabilities (i.e. XSS, SQLi) as well. Ref: https://owasp.org/www-project-pygoat/

### SAST Scan with Bandit (or Snyk):
SAST (Static Application Security Testing): static analysis of the application source code for exploits, bugs, vulnerabilites (Bandit)

### Container Image Scanning with Docker Scout (or Snyk):
Identify vulnerabilities in built images (DockerHub Scout Image Scanner)

Ref: Docker Scout Links:
- Docker Scout: https://docs.docker.com/scout/
- Docker Scout CLI: https://docs.docker.com/engine/reference/commandline/scout/
- Docker Scout GitHub Action: https://github.com/docker/scout-action

Note: We can use Snyk instead of Scout (Bitbucket also use Snyk)

Ref: Snyk Links:
- https://snyk.io/partners/docker/
- https://github.com/snyk/actions
- 
### How to generate scan reports (Bandit & Scout)

### How to analyze scan reports (json report files)

Ref: 
https://www.defectdojo.org

