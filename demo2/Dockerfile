FROM registry.access.redhat.com/ubi7/python-36:1

RUN pip install boto3

COPY hi.txt /opt/hi.txt

CMD ["python", "-m", "http.server", "8080"]
