## Hilfe bei Powershell
### Datei herunterladen
PS > `Invoke-WebRequest -Url URL_TO_DOWNLOAD -OutFile FILE_PATH`

## Docker
PS > `docker ps`

PS > `docker container ls`

PS > `docker image ls`

Löscht Image:

PS > `docker rmi IMAGE_TO_DELETE`

Ladet ein Image herunter:

PS > `docker pull IMAGE_ID`

Das ist aber nicht notwendig, denn `docker build` macht das auch.

Erstellt ein neues Image aus einem Dockerfile:

PS > `docker build -t TAG_FOR_IMAGE .`

Instanziiert ein neues Container:

PS > `docker run --name NAME_FOR_IMAGE IMAGE_ID`

Ruft ein Terminal in einem gestarteten Container:

PS > `docker exec -it IMAGE_NAME /bin/bash`
