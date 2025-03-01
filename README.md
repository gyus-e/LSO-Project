# LSO-Project
Dialogare coi robot.

## Usage
  ### Requisiti
  - [Java SDK versione 8](https://adoptium.net/temurin/releases/?package=jdk&version=8), [gcc](https://gcc.gnu.org/) e [make](https://www.gnu.org/software/make/) (per eseguire localmente).
  - [Docker](https://www.docker.com/) (per eseguire su container).
  - Emulatore di Furhat, ottenibile registrandosi su [Furhat.io](https://furhat.io/).
  - Key per le API di OpenAI, ottenibile registrandosi su [OpenAI API Platform](https://openai.com/api/). 
    La key puó essere salvata tra le variabili d'ambiente, oppure nella root della repository, in un file `.env`, il cui corpo deve contenere la seguente riga:
  
    `OPENAI_API_KEY=<api-key>`
    
  Sostituendo `<api-key>` con la key ottenuta.


  ### Eseguire su container:
  ```sh
  docker compose up
