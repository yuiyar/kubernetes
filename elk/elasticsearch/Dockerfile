FROM elasticsearch:7.10.1
COPY --chown=elasticsearch:elasticsearch elastic-certificates.p12 /usr/share/elasticsearch/config
RUN ["/bin/bash", "-c", "cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime"]
