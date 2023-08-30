FROM centos:7
LABEL version="1.0" description="This is a test image" by="author"
ENV WORKPATH /opt
WORKDIR $WORKPATH

RUN yum install -y wget net-tools vim gcc

ADD test.sh /opt/
RUN chmod +x /opt/test.sh
CMD ["/bin/bash","/opt/test.sh"]
CMD /bin/bash