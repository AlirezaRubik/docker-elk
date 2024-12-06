ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION:-8.15.5}
# RUN set -eux; \
# 	mkdir /state; \
# 	chmod 0775 /state; \
# 	chown elasticsearch:root /state

# USER elasticsearch:root
ENTRYPOINT ["/entrypoint.sh"]

