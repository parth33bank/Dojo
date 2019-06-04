FROM ubuntu:latest
MAINTAINER PK "partheeban.kandasamy@gmail.com"
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
RUN chmod 644 app.py
ENTRYPOINT ["python"]
CMD ["app.py"]
