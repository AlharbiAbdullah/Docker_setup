FROM python:3.11-slim 

RUN mkdir code 

WORKDIR /code 

COPY . /code 

RUN pip install jupyterlab \
    && pip install pandas \
    && pip install psycopg2-binary \
    && pip install duckdb \
    && pip install jupysql \
    && pip install duckdb-engine 

