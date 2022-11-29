FROM python:3.9

RUN mkdir /code

ADD requirements.txt ./

RUN pip install -r requirements.txt

ADD ./ /code/

WORKDIR /code
