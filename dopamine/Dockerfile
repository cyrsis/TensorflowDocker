FROM tensorflow/tensorflow:latest-gpu-py3
#FROM tensorflow/tensorflow:1.3.0-gpu-py3

RUN apt-get update
RUN apt-get install -y cmake
RUN apt-get install -y git
RUN pip install dopamine-rl
RUN pip install atari-py
RUN git clone https://github.com/google/dopamine.git
RUN cd dopamine
RUN apt install -y libsm6
RUN apt install -y libxrender1







#RUN pip install scikit-image
#RUN pip install git+https://github.com/jakevdp/JSAnimation.git
#RUN pip install scikit-image
#RUN apt-get update && apt-get install -y python-pyglet
#RUN pip install scikit-image
#CMD ["/run_jupyter.sh"]