FROM ubuntu:16.04

WORKDIR /mydir 
COPY script.sh .
RUN chmod 744 ./script.sh     
RUN apt-get update && apt-get install -y curl
CMD ["./script.sh"]