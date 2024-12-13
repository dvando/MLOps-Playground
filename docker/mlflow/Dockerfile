FROM ghcr.io/mlflow/mlflow:v2.17.2

RUN apt-get -y update && \
apt-get -y install python3-dev build-essential pkg-config && \
pip install --upgrade pip && \
pip install psycopg2-binary boto3

# RUN  mlflow db upgrade postgresql://${POSTGRES_USER}:${POSTGRES_PASSWORD}@127.0.0.1:8765/mlflow

CMD ["bash"]
