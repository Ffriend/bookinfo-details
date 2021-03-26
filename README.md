# Bookinfo Details Service

Details service has been developed with Ruby

## How to run with Docker

```bash
# Build Docker Image for details service
docker build -t details .

# Run details service on port 8080
docker run -d --name details -p 8080:8080 details
```

## How to run with Docker Compose

```bash
docker-compose up
```

* Test with path `/details/***` and `/health`