FROM almalinux:9
RUN mkdir /tmp/docker
# RUN cd /tmp/docker -- cd directory doesn't work here
WORKDIR /tmp/docker
RUN pwd
RUN echo "Hello" > hello.txt
CMD [ "sleep" , "100" ]