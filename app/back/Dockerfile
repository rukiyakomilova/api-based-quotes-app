FROM python:3.6

WORKDIR /app

COPY requirements.txt /app 
COPY back.py /app

RUN pip install -r requirements.txt

EXPOSE 3000
CMD python back.py

