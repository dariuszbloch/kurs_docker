FROM nginx:alpine
COPY html /usr/share/nginx/html

HEALTHCHECK CMD curl -f http://localhost || exit 1
