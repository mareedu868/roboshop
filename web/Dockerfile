FROM nginx
RUN rm -rf /usr/share/html/
RUN static /usr/share/html/
ENTRYPOINT ["nginx", "-g", "daemon off;"]