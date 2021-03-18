FROM python:3.9.2-slim

WORKDIR /src

COPY requirements.txt /src
RUN pip install -r requirements.txt

COPY . /src

ENTRYPOINT ["python3"]
CMD ["./flaskapp.py"]
