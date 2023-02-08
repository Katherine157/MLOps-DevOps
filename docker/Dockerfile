FROM continuumio/miniconda3:latest
LABEL version="1.0"

RUN apt-get install python3

COPY 1.sh app/1.sh

EXPOSE 6000

CMD ["app/1.sh"]
