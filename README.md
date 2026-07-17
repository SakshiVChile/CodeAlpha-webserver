# CodeAlpha DevOps Internship

## Task 4 - Web Server using Docker

### Objective

Deploy a web server using Docker and serve a custom HTML webpage.

### Technologies Used

- Docker (Podman compatible on RHEL 9)
- Nginx
- HTML
- Linux (RHEL 9)

### Files

- Dockerfile
- index.html

### Build Docker Image

```bash
docker build -t sakshi-webserver:v1 .
```

### Run Container

```bash
docker run -d --name sakshi-web -p 8080:80 sakshi-webserver:v1
```

### Verify

Open

http://localhost:8080

### Author

Sakshi Chile
