# branching-strategy-workshop-demo

## Building With Docker

To build a Docker image:

`./gradlew clean build && docker image build -t workshop-demo:latest .`

To start a new Docker container and access the application:

`docker run --name workshop-demo -d -p 8090:8090 -t workshop-demo:latest`

To see the logs for the container:

`docker container logs workshop-demo`