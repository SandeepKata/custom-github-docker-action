FROM node:16

WORKDIR /usr/src/app

COPY entrypoint.sh .

RUN chmod +x entrypoint.sh

ENTRYPOINT ["/usr/src/app/entrypoint.sh"]
