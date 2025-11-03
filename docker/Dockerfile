FROM nginx:alpine


RUN rm -rf /usr/share/nginx/html/index.html
COPY ./myapp/index.html /usr/share/nginx/html/index.html

COPY ./myapp/nginx.conf /etc/nginx/nginx.conf

ENTRYPOINT ["nginx", "-g", "daemon off;"]