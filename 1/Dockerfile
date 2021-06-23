FROM ubuntu:18.04
RUN apt-get update
RUN apt-get install git python3 python3-pip -y
RUN git clone https://github.com/anfederico/flaskex.git
RUN cd Flaskex
RUN pip3 install -r requirements.txt
RUN python3 app.py