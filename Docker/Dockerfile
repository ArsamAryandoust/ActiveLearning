FROM tensorflow/tensorflow:nightly-gpu

RUN apt update
RUN apt upgrade -y

RUN pip install xlrd
RUN pip install Pillow
RUN pip install numpy
RUN pip install scipy
RUN pip install sklearn
RUN pip install scikit-image
RUN pip install pandas
RUN pip install matplotlib
RUN pip install pydot

WORKDIR /ActiveLearning/src

CMD python main.py

