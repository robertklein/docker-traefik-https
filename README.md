# docker-traefik-https

This is the example how to run traefik proxy (`traefik` direcotry) in docker and 2 separate applications (`app` and `app2` direcotry) and enable https.

Based on https://felixwiedmann.de/traefik-on-docker/

Create network

    docker network create web

Create acme.json

	sudo touch /opt/traefik/acme.json && sudo chmod 600 /opt/traefik/acme.json

Run `docker-compose up --build` inside of traefik dir, same for app and app2 dirs.
