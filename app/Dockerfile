FROM spark:3.5.0-python3
RUN mkdir -p /opt
ADD ./network_count.py /opt/network_count.py
CMD spark-submit /opt/network_count.py localhost 9999
