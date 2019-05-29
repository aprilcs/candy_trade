FROM registry.codeocean.com/codeocean/miniconda3:4.6.14-python3.7.3-ubuntu18.04

ARG DEBIAN_FRONTEND=noninteractive

RUN conda install --yes \
      jupyter==1.0.0 \
      jupyterlab==0.35.4 \
      matplotlib==3.0.2 \
      pandas==0.24.0 \
    && conda clean --yes --all
