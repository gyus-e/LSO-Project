# LSO-Project
Dialogare coi robot.

## Description
Progetto di Laboratorio di Sistemi Operativi anno 2024/2025, Universitá degli Studi di Napoli Federico II, Corso di Laurea in Informatica, DIETI.

Il progetto consiste in un'architettura client-server.
Il client ha il compito di fare da intermediario tra un robot ed una persona, permettendo al robot di fare domande per stabilire quale personalità ha l'interlocutore (livello di estroversione, amicalità, coscienziosità, stabilità emotiva, apertura a nuove esperienze). Il server riceve le risposte dell'utente e calcola una stima della personalitá da inviare al client. Ottenuta una stima della personalitá dal server, il client usa openai per la gestione dei dialoghi.

Il questionario di personalitá utilizzato è il [TIPI](https://gosling.psy.utexas.edu/scales-weve-developed/ten-item-personality-measure-tipi/).
Il robot utilizzato è [Furhat](https://docs.furhat.io/).

## Usage
  ### Requirements
  - [gcc](https://gcc.gnu.org/) e [make](https://www.gnu.org/software/make/) (per compilare localmente il server).
  - Sistema operativo compatibile con standard Posix (per eseguire localmente il server).
  - [Java SDK versione 11](https://adoptium.net/temurin/releases/?package=jdk&version=11) (per compilare e eseguire localmente il client).
  - [Docker](https://www.docker.com/) e [docker-compose](https://docs.docker.com/compose/) (per eseguire su container).
  - Furhat SDK, ottenibile registrandosi su [Furhat.io](https://furhat.io/).
  - Key per le API di OpenAI, ottenibile registrandosi su [OpenAI API Platform](https://openai.com/api/). 
    - La key deve essere salvata in un file nella root della repository col nome `openai_api_key.txt`.

  ### Eseguire localmente:
  Eseguire individualmente il server e il client. Per istruzioni su come farlo, consultare i README delle relative repository.
  
  ### Eseguire su container:
  ```sh
  docker compose up
 