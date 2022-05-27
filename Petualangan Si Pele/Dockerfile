FROM python:latest

COPY kebutuhan.txt .

RUN pip install -r kebutuhan.txt
# RUN apt-get update && apt-get upgrade -y && apt-get install -y \ 
#     libasound2

COPY Petualangan_Si_Pele.py .
COPY Aset ./Aset

CMD ["python","Petualangan_Si_Pele.py"]
