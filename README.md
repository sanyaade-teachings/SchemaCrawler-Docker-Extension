# Extension for the SchemaCrawler Docker Image

> See [Docker Image for SchemaCrawler](https://github.com/sualeh/SchemaCrawler-Docker)

SchemaCrawler Docker image that is used to include any additional local jar files, such as proprietary JDBC drivers that cannot be publicly distributed. Intended for privately built Docker images.

-----

## Build and Deploy Docker Image

Include any additional jar files in the project directory.

In the directory containing the Docker file, run
```
docker build -t sualeh/schemacrawler-extension:latest .
```

Do not deploy to Docker Hub.
