
# syntax=docker/dockerfile:1
FROM python:3.8-slim-buster

COPY credentials.json  /
COPY requirements.txt  /
ADD main.py  /
RUN pip3 install -r requirements.txt
CMD ["python3","main.py"]

# Para crear la imagen : docker build . -t readerservice 

#Para ejecutar la imagen : docker run --net=host readerservice

