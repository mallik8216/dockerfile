ARG version
FROM almalinux:${version:-9}
ENV course="Devops and Amazon" \
    trainer="shiva yadav" \
    duration="3months"
 ARG username=shivayadav
RUN echo "Hello User: ${username}, image version: ${version}"  > /tmp/devops.txt
#RUN echo "Hello ${trainer}" > /var/tmp/devops.txt
CMD [ "sleep","1800" ]



#ARG ${username:-some_user} ---ve can override Arg  by this