# docker-traefik-https

Based on https://felixwiedmann.de/traefik-on-docker/

Create network

    docker network create web

Create acme.json

	sudo touch /opt/traefik/acme.json && sudo chmod 600 /opt/traefik/acme.json