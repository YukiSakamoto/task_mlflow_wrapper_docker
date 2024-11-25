FROM python:3.11
WORKDIR /mlflow
#RUN pip install --upgrade pip
RUN pip install --progress-bar off mlflow
#RUN ulimit -u 65535
CMD ["mlflow", "server", "--host=0.0.0.0"]
