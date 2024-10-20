# BASE
FROM python:3.11-alpine

#log
ENV PYTHONUNBUFFERD 1

COPY ./requirements.txt /requirements.txt
RUN pip install -r /requirements.txt

WORKDIR /app

CMD [ "ash", "entrypoint.sh" ]