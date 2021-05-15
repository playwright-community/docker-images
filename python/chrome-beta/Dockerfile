FROM ubuntu:focal

RUN apt-get update -y && apt-get install -y \
    python3.8 \
    python3.8-distutils \
    curl 

RUN ln -s /usr/bin/python3 /usr/bin/python

RUN curl https://bootstrap.pypa.io/get-pip.py | python

RUN curl -O https://dl.google.com/linux/direct/google-chrome-beta_current_amd64.deb 

RUN DEBIAN_FRONTEND=noninteractive apt install ./google-chrome-beta_current_amd64.deb -y && \
    rm -rf ./google-chrome-beta_current_amd64.deb

RUN pip install pip -U && \ 
    pip install playwright

RUN DEBIAN_FRONTEND=noninteractive playwright install-deps chromium

RUN playwright install ffmpeg
