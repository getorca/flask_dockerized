FROM python:3.4-onbuild
MAINTAINER Lawrence Stewart
RUN apt-get update -y
ADD . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
