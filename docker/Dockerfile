FROM debian:stretch

# install curl
RUN apt-get update && apt-get install -y curl

RUN mkdir /opt/software
ADD run.sh /opt/software/

ENTRYPOINT ["/bin/bash"]
