FROM nginx:1.17
VOLUME /tmp
ENV LANG en_US.UTF-8
COPY /dist/ /usr/share/nginx/html/
COPY /default.conf /etc/nginx/conf.d/
EXPOSE 80
EXPOSE 443
