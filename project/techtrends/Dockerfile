FROM python:2.7

LABEL maintainer="Pawan Kumar"
COPY . /app
WORKDIR /app
ENV FLASK_APP=app.py
RUN pip install -r requirements.txt
CMD [ "python", "app.py" ]
EXPOSE 7111

