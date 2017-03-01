FROM s1artie/pulp_crane:latest

MAINTAINER Rene Schneider <rene.schneider@gebit.de>

ADD crane.conf /etc/crane.conf

ENTRYPOINT ["/usr/sbin/httpd"]
CMD ["-D", "FOREGROUND"]
