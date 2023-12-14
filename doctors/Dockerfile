FROM python:3.9

WORKDIR /app
COPY . /app

RUN pip install --trusted-host pypi.python.org Flask

EXPOSE 9090

CMD ["python", "app.py"]