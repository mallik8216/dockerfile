# FROM almalinux:9
# RUN mkdir /var/tmp/mydir-daemo
# RUN cd /var/tmp/mydir-daemo
# RUN pwd
# RUN echo "hello from mydir-demo" > hello.txt
# CMD [ "sleep","100" ]

# CD wont work to change directory instead of this Go with WORKDIR


FROM almalinux:9
RUN mkdir /var/tmp/mydir-daemo
WORKDIR  /var/tmp/mydir-daemo
RUN pwd
RUN echo "hello from mydir-demo" > hello.txt
CMD [ "sleep","100" ]


#   in docker cd vill not vork .Use only WORKDIR to  chage  login to container at  given directory.