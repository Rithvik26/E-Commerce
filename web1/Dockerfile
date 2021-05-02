FROM nginx:alpine


WORKDIR /usr/share/nginx/html
COPY . /usr/share/nginx/html
EXPOSE 80

CMD cd /usr/share/nginx/html; nginx -g 'daemon off;'
