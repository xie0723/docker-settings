FROM locustio/locust:2.14.1
WORKDIR /home/locust
ADD . .
ADD locust/* /home/locust
RUN pip install -r requirements.txt
CMD ["locust"]