FROM python:3.9

RUN pwd
WORKDIR .

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY app.py .

EXPOSE 5000

CMD ["python", "app.py"]

