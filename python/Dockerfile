FROM python:2.7-slim

WORKDIR /app

ADD . /app

RUN pip install -i http://mirrors.aliyun.com/pypi/simple/ -r requirements.txt

EXPOSE 80

ENV NAME World

CMD ["python","app.py"]

