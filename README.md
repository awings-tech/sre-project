# SRE Project

A small Flask app used to practice SRE and DevOps skills: containers,
Kubernetes, monitoring and incident response.

## Run it

    docker build -t sre-app:v1 .
    docker run -d -p 8080:8080 --name sre-app sre-app:v1
    curl localhost:8080/health

## Roadmap

- [x] Flask app with /health endpoint
- [x] Dockerfile
- [ ] GitHub Actions pipeline
- [ ] Kubernetes deployment
- [ ] Prometheus + Grafana monitoring
- [ ] Deploy on labhyam.in
