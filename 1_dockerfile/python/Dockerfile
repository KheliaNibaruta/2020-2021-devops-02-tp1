FROM python:2.7-alpine3.9

WORKDIR /GitHub/2020-2021-devops-02-tp1/1_dockerfile/python

COPY requirements.txt .
RUN pip install -r requirements.txt

EXPOSE 5000

CMD python2 ./app.py