# uwsgiがpython3.9以下でしか使えず、whisperがpython3.8以上しか使えない様子のため、3.9に設定
FROM python:3.9
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
RUN pip install -r requirements.txt
ADD . /code/
