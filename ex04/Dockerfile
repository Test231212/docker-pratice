FROM ubuntu

WORKDIR /etc/init.d

RUN apt-get update && apt-get install -y nginx

CMD ["sh", "-c", "./nginx start && tail -f /dev/null"]

# docker build -t code/nginx .
# docker run -dit code/nginx bash
# docker attach 컨테이너아이디

#docker build -t code/nginx .
#docker run -dit -p 8000:80 code/nginx 