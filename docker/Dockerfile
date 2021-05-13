FROM python:3
WORKDIR /rtsp-server/
RUN apt update
RUN pip install pycairo
RUN apt -y install libgirepository1.0-dev
RUN pip install PyGObject
RUN apt -y install gir1.2-gst-rtsp-server-1.0