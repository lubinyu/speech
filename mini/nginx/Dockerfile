FROM scratch
MAINTAINER lbbniu <lbbniu@qq.com>
ADD rootfs.tar.gz /
WORKDIR /data
EXPOSE 80 443
ENTRYPOINT ["/sbin/nginx"]
CMD ["-g","daemon off;"]