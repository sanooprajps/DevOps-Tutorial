FROM ubuntu
MAINTAINER sanoop
RUN apt-get update
RUN apt-get install python
ADD demo-app.py /home/demo-app.py
CMD ["/home/demo-app.py"]
ENTRYPOINT ["python"]
