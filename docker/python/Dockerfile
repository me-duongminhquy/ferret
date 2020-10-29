FROM python:3.8-alpine

WORKDIR /usr/src/app

COPY ./docker/python/requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY ./src/py .

CMD [ "python", "./server.py" ]