FROM nginx:alpine
MAINTAINER Z. d. Peacock <zdp@thoomtech.com>

EXPOSE 9201 5602
ENTRYPOINT ["/sbin/tini", "-g", "--"]
CMD ["nginx", "-g" "'daemon off;'"]