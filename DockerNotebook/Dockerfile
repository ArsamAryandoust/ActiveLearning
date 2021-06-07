FROM tensorflow/tensorflow:2.5.0-gpu

# RUN apt-get update
# RUN apt-get upgrade -y

RUN pip install xlrd
RUN pip install Pillow
RUN pip install numpy
RUN pip install scipy
RUN pip install sklearn
RUN pip install scikit-image
RUN pip install pandas
RUN pip install matplotlib

RUN pip install jupyter 

CMD jupyter notebook --ip 0.0.0.0 --port 1111 --no-browser --allow-root

