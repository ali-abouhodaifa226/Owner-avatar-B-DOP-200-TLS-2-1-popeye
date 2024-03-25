FROM python:latest
WORKDIR /app
COPY ./ /app
RUN pip3 install -r /app/requirements.txt
EXPOSE 80
CMD flask run --host=0.0.0.0 --port=80