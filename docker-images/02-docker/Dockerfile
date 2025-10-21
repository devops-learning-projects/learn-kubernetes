FROM            redhat/ubi9
ADD             sample.txt /opt/sample.txt
ARG             URL
# use "--build-arg" to set build time variable. Ex. --build-arg URL=google.com
RUN				echo $URL
ENV             URL1=google.com
USER            bin
WORKDIR         /etc
ENTRYPOINT      id