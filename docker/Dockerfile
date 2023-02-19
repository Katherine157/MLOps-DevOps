FROM continuumio/miniconda3:latest
LABEL version="1.0"

ENV DIRPATH=/opt/docker/
WORKDIR $DIRPATH/$DIRNAME

RUN apt-get install python3
RUN pip install mlflow
RUN pip install boto3
RUN pip install pymysql

#RUN chmod +x 1.sр
COPY 1.sh /app/1.sh

EXPOSE 6000

CMD ["/app/1.sh"]

