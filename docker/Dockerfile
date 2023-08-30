FROM python:3.10.8-slim-bullseye

RUN apt update && \
    apt install -y git libgl1-mesa-glx

RUN pip install \
        git+https://github.com/CadQuery/cadquery.git \
        dataclasses-json \
        numpy \
        scipy \
        solidpython \
        GitPython

WORKDIR /app
