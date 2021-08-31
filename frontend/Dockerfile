FROM python:3.7

WORKDIR /testingjenkins1/frontend

RUN pip install -r requirements.txt

COPY . .

EXPOSE 5000

ENTRYPOINT ["python", "app.py"]
