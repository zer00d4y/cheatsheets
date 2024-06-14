# Docker 

| **Command** | **Description** |
| --------------|-------------------|
| `docker -d` | Start the docker daemon |
| `docker --help` | Get help with Docker. Can also use –help on all subcommands |
| `docker info` | Display system-wide information |
| `docker build` | Builds an image from a Dockerfile. |
| `docker buildx` | Builds a Docker images for multiple architectures and platforms concurrently |
| `docker buildx build -t <image_name> <file>` | Builds a Docker images for multiple architectures and platforms concurrently |
| `docker build -t <image_name>` | Build an Image from a Dockerfile | 
| `docker build -t <image_name> . –no-cache` | Build an Image from a Dockerfile without the cache |
| `docker build . -t` | Builds the image and tags the image id. |
| `docker CLI` | Start the Docker command line interface. |
| `docker container rm`	| Removes a container. |
| `docker images` |	Lists the images. |
| `docker rmi <image_name>` | Delete an Image |
| `docker image prune` | Remove all unused images |
| `docker ps`	| Lists the containers. |
| `docker ps -a`	| Lists the containers that ran and exited successfully. |
| `docker pull`	| Pulls the latest image or repository from a registry. |
| `docker push`	| Pushes an image or a repository to a registry. |
| `docker run`	| Runs a command in a new container. |
| `docker run -p`	| Runs the container by publishing the ports. |
| `docker stop`	| Stops one or more running containers. |
| `docker stop $(docker ps -q)`	| Stops all running containers. |
| `docker tag`	| Creates a tag for a target image that refers to a source image. |
| `docker –version`	| Displays the version of the Docker CLI. |
| `export MY_NAMESPACE`	| Exports a namespace as an environment variable. |
| `ibmcloud cr images`	| Lists images in the IBM Cloud Container Registry. |
| `ibmcloud cr login`	| Logs your local Docker daemon into IBM Cloud Container Registry. |
| `ibmcloud cr namespaces`	| Views the namespaces you have access to. |
| `ibmcloud cr region-set`	| Ensures that you are targeting the region appropriate to your cloud account. |
| `ibmcloud target`	| Provides information about the account you’re targeting. |
| `ibmcloud version` | Displays the version of the IBM Cloud CLI. |
