FROM python:3.8-alpine
RUN mkdir /app
ADD . /app
WORKDIR /app
COPY app.py ./app
CMD ["python", "app.py"]