FROM nginx

COPY html /usr/share/nginx/html
COPY conf/nginx.conf /etc/nginx/conf.d/default.conf

ENTRYPOINT ["nginx", "-g", "daemon off;"]

# docker build -t ex05 .
# docker run -dit 8080:80 ex05
