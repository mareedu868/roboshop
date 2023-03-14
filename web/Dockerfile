FROM nginx
RUN rm -rf /usr/share/html/
ADD static /usr/share/html/
ENTRYPOINT ["nginx", "-g", "daemon off;"]