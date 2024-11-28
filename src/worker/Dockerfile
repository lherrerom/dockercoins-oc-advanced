FROM python:alpine
RUN pip install Redis requests && apk add redis
COPY worker.py .
CMD python worker.py
