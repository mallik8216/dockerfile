FROM almalinux:9
RUN  dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/mallik8216/shellscript/refs/heads/main/01-hello.sh /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD  ["nginx" , "-g","daemon off ;"]