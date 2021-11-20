FROM nginx:1.21.3-alpine
# should upgrade specific version
# RUN apk upgrade busybox curl libcurl ssl_client
RUN apk update & apk upgrade
USER nginx
EXPOSE 80
STOPSIGNAL SIGQUIT
CMD ["nginx", "-g", "daemon off;"]
