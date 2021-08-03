# Run Postman Collections Using Docker

In this example I have created a postman collection based on spotify.
To get a positive report you need to generate a new [Token](https://developer.spotify.com/console)

[![docker-compose-actions-workflow](https://github.com/fziviello/docker-postman-newman/actions/workflows/main.yml/badge.svg)](https://github.com/fziviello/docker-postman-newman/actions/workflows/main.yml)

# Build Docker Image

```
docker build .
```
# Run and Generate newman's report

```
docker-compose up
```
# Remove container after run

```
docker-compose rm -f
```
