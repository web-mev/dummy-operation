FROM debian:stretch

# install curl
RUN apt-get update && apt-get install -y curl

RUN mkdir /opt/software
ADD run.sh /opt/software/
RUN chmod +x /opt/software/run.sh

ENTRYPOINT ["/bin/bash"]
