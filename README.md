# 3 things every developer should know about K8s security

[![Build Status](https://oss.cloudogu.com/jenkins/buildStatus/icon?job=cloudogu-github%2Fk8s-security-3-things%2Fmaster)](https://oss.cloudogu.com/jenkins/job/cloudogu-github/job/k8s-security-3-things/job/master/)

Slides for the "3 things every developer should know about K8s security" talk by 
[schnatterer](http://github.com/schnatterer/).

See
* [slides](https://cloudogu.github.io/k8s-security-3-things)
* [demos](https://github.com/cloudogu/k8s-security-demos)

This presentation uses reveal.js.
For more info on how to continuously deliver presentations see [cloudogu/reveal.js-docker](https://github.com/cloudogu/reveal.js-docker/).

# Deployment

```bash
# Development mode (with live reloading)
./startPresentation.sh

# Production Mode (smaller, more secure, just a static HTML site served by NGINX)
docker build -t prod .
docker run -p 8080:8080 prod
```