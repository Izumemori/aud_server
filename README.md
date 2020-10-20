# Docker Image für Jupyter Notebook mit algoviz

## Installation

0. Docker installieren

    Für Ubuntu:

        apt-get install docker.io

1. Docker Image herunterladen:

        docker pull docker.pkg.github.com/koplas/aud_server/aud-server:main

2. Docker Image starten:

        docker run --name aud_container -p 8888:8888 -it docker.pkg.github.com/koplas/aud_server/aud-server:main

3. Im Webrowser `http://localhost:8888` öffnen

## Hinweis

Um den Container mit gleichen Inhalt später erneut zu starten:

    docker start aud_container
