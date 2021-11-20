FROM nginx:1.21.3-alpine
RUN apk upgrade busybox curl libcurl ssl_client
USER nginx
EXPOSE 80
STOPSIGNAL SIGQUIT
CMD ["nginx", "-g", "daemon off;"]
