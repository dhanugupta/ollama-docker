## Installing Ollama with open-webui Docker Compose
This repository provides a comprehensive setup for running two services: ollama and ollama-webui. 
Our goal is to create a seamless experience for users by providing a stable foundation for both services.
Running Large Language Models (LLMs) can be resource-intensive, so we recommend using a machine with at least 16GB of RAM and 4 CPU cores.

## Prerequisites

Make sure you have Docker and Docker Compose installed on your machine.
- Docker Desktop : https://docs.docker.com/desktop/

## Getting Started

Follow these steps to get the services up and running:

- [x] Clone the Repository
- [x] git clone <repository-url>
- [x] cd <repository-directory>
- [x] Start the Services Use Docker Compose to start the services:
``` docker-compose up -d ```
- [x] Login via http://localhost:3008
- [x] Register a new user and you are all set to start experiment with Ollama
~~- [x] Using docker exec to pull ``llama3.2:1b`` model [for more model: https://ollama.com/search]
``` docker exec -it ollama ollama pull llama3.2:1b ```~~
- [x] added entrypoint to fetch model async

- [x] Stop the services
```docker-compose down```