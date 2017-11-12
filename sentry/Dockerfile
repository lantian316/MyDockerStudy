FROM docker.io/sentry

RUN mv /etc/localtime /etc/localtime.bak \
&& cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime

ADD server.py /usr/local/lib/python2.7/site-packages/sentry/conf