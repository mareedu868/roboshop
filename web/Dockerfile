FROM nginx
RUN rm -rf /usr/share/nginx/html/
COPY static /usr/share/nginx/html/
RUN rm -rf /etc/nginx/default.d/
RUN rm -rf /etc/nginx/conf.d/
COPY default.conf /etc/nginx/default.d/roboshop.conf
COPY default.conf /etc/nginx/conf.d/roboshop.conf