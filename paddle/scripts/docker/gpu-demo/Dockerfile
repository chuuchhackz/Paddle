FROM nvidia/cuda:7.5-cudnn5-devel-ubuntu14.04
MAINTAINER PaddlePaddle Dev Team <paddle-dev@baidu.com>
COPY build.sh /root/
ENV WITH_GPU=ON
ENV IS_DEVEL=ON
ENV WITH_DEMO=ON
ENV PIP_INSTALL_ARGS ""
ENV PIP_GENERAL_ARGS ""
RUN cd /root/ && bash build.sh
