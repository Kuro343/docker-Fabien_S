FROM debian

LABEL hub_url="Kuro343/docker-Fabien_S_api-backend"

WORKDIR /usr/bin/
COPY --chown=root:root ./api.py ./

RUN apt-get update -y && apt-get install -y python-requests python-flask
EXPOSE 8001
CMD api.py
