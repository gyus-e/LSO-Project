# LSO-Project
Dialogare coi robot.

## Usage
  ### Requirements
  - [Java SDK versione 8](https://adoptium.net/temurin/releases/?package=jdk&version=8), [gcc](https://gcc.gnu.org/) e [make](https://www.gnu.org/software/make/) (per eseguire localmente).
  - [Docker](https://www.docker.com/) e [docker-compose](https://docs.docker.com/compose/) (per eseguire su container).
  - Furhat SDK, ottenibile registrandosi su [Furhat.io](https://furhat.io/).
  - Key per le API di OpenAI, ottenibile registrandosi su [OpenAI API Platform](https://openai.com/api/). 
    - La key deve essere salvata in un file nella root della repository col nome `openai_api_key.txt`.


  ### Eseguire su container:
  ```sh
  docker compose up
