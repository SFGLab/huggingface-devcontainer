FROM nvcr.io/nvidia/pytorch:23.11-py3

RUN apt-get update && apt-get -y install \
    build-essential

RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir 'transformers[torch]' deepspeed accelerate datasets tokenizers evaluate black
