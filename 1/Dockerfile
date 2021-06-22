FROM ubuntu:18.04
RUN apt update
RUN apt install git python3
RUN git clone https://github.com/anfederico/flaskex.git
RUN cd flaskex
RUN pip3 install -r requirements.txt
RUN python3 app.py