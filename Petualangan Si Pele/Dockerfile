
FROM python:latest

COPY . .

RUN apt-get update -y

RUN apt-get install python -y

RUN pip install -r kebutuhan.txt 

ENV DISPLAY=host.docker.internal:0.0

CMD ["python", "./Petualangan_Si_Pele.py"]
