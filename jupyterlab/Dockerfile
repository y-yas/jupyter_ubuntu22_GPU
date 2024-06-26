FROM ubuntu:22.04

RUN apt-get update
RUN apt install -y \
	python3 \
	python3-pip \
	postgresql-client 
RUN pip install --upgrade pip
RUN python3 -m pip install jupyterlab psycopg2-binary pandas ipython-sql
