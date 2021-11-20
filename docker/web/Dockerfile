FROM nginx:1.21.3-alpine
# 固定バージョンを指定したい
# https://blog.stormcat.io/post/entry/alpine-entry-apk/
RUN apk update busybox curl=7.79.0-r0 libcurl ssl_client
USER nginx
EXPOSE 80
STOPSIGNAL SIGQUIT
CMD ["nginx", "-g", "daemon off;"]
