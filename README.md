# nginx
alpine nginx with root directory volume


docker run --rm -d -v "$PWD/www":"/usr/share/nginx/html" -P mercstudio/nginx
