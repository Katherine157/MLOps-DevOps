FROM continuumio/miniconda3:latest
LABEL version="1.0"

ENV DIRPATH=/opt/docker/
WORKDIR $DIRPATH/$DIRNAME

RUN apt-get install python3

#RUN chmod +x 1.sр
COPY 1.sh /home/app/1.sh

EXPOSE 6000

CMD ["/home/app/1.sh"]

