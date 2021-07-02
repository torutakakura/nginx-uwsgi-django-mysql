# アプリケーション環境構築
FROM python:3.8
ENV PYTHONUNBUFFERED 1
RUN mkdir /memofy
WORKDIR /memofy
ADD requirements.txt /memofy/
RUN pip install -r requirements.txt
ADD . /memofy/