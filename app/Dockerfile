FROM python:3.13-alpine

WORKDIR /app

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . .

EXPOSE 5500
CMD [ "python3", "app.py" ]
