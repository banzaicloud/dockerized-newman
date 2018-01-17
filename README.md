# Dockerized Newman

For detailed reference please check this [post](https://banzaicloud.com/blog/helm-rest-api/).

# Docker image for running e2e tests with Postman
Docker image for running end to end tests against the BanzaiCloud Pipeline API
(Extends the original postman image with environment configuration upon container start)

## Example

```docker run -e PIPELINE_ENDPOINT="http://ppl:9090/" -e POSTMAN_COLLECTION="https://www.getpostman.com/collections/56684ef61ee236e8f30d"```

## References
https://hub.docker.com/r/postman/newman_alpine33/
https://www.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman
https://github.com/postmanlabs/newman-docker
https://github.com/jwilder/dockerize
