# FIRST DOCKER FILE IMPLEMENTING SHELL SCRIPT
FROM ubuntu:18.04
LABEL MAINTAINER rekha@priyanka.com
copy Sample.sh /code/Sample.sh
RUN chmod +x /code/Sample.sh
ENTRYPOINT ["sh","/code/Sample.sh"]
CMD ["/etc/hosts"]
