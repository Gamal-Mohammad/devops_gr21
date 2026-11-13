# Mini Jumia Clone – DevOps Group 21

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Apache](https://img.shields.io/badge/Apache_httpd-D22128?logo=apache&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

> A Jumia-style e-commerce landing page, containerised with Apache httpd.

## Overview

Static web page containerised with **Apache httpd**. The repository is used in the DevOps training track to practise Git, building Docker images and running them as containers.

## Tech Stack

- **Docker**
- **Apache httpd**
- **HTML/CSS**
- **Git**

## Repository Structure

```text
Dockerfile
index.html
README.md
welcome.txt
```

## Getting Started

### Run with Docker

```bash
git clone https://github.com/Gamal-Mohammad/devops_gr21.git
cd devops_gr21
docker build -t devops-gr21 .
docker run -d --name devops-gr21 -p 8080:80 devops-gr21
```

Then open http://localhost:8080.

## Author

**Gamal Mohammad**

[![GitHub](https://img.shields.io/badge/GitHub-Gamal--Mohammad-181717?logo=github)](https://github.com/Gamal-Mohammad)
