FROM python:3.7

RUN mkdir /app
COPY model/ /app/
COPY preprocessing/ /app/
COPY utils/ /app/
WORKDIR /app
CMD ["python","model.py"]

