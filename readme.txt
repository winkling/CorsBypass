docker build -t cors-bypass .
docker run --rm -it -p 9981:9981 cors-bypass

Ref:
https://enable-cors.org/server_nginx.html