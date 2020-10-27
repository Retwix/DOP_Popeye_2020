FROM python:latest
RUN mkdir /app
WORKDIR /app
COPY . /app/
COPY app.py .
RUN pip3 install -r requirements.txt
EXPOSE 80
CMD flask run --host=0.0.0.0 --port=80