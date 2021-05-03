FROM python:3.7

RUN mkdir /app
COPY docker/ pipeline/ /app/
WORKDIR /app
CMD ["python","model/model.py"]

