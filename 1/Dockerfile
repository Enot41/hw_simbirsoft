FROM python:3
RUN apt-get update
RUN apt-get install git  -y
RUN git clone https://github.com/anfederico/flaskex.git
RUN pip3 install -r flaskex/requirements.txt
EXPOSE 5000
CMD [ "python", ".flaskex/app.py" ]