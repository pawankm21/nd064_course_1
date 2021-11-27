FROM python:2.7

LABEL maintainer="Pawan Mishra"

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt
RUN python init_db.py
CMD ["python", "app.py"]
EXPOSE 3111
