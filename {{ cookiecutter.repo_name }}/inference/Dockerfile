FROM nvcr.io/nvidia/tritonserver:24.04-py3

COPY inference/requirements.txt /requirements.txt
RUN pip3 install -r /requirements.txt

VOLUME /models
