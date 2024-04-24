FROM ubuntu:nobile-20231221
WORKDIR /mynginx
RUN abt update
RUN apt install nginx
COPY table1.html /usr/share/nginx/html
ADD table2.html.tar /usr/share/nginx/html
EXPOSE 80
CMD [ "/usr/share/nginx", "-g", daemon off; ]
