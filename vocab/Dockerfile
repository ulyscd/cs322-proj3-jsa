FROM python:3
MAINTAINER Ulys Chauncey Drumrongthai "ulys@uoregon.edu"

COPY . /app 
WORKDIR /app 

RUN pip install -r requirements.txt 
CMD ["python", "flask_vocab.py"]
