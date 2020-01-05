FROM nginx:1.17.6

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d/serve-static.conf

RUN mkdir -p /www
COPY public /www/data

RUN alias ll="ls -la"
