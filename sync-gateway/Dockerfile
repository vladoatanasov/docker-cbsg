FROM couchbase/sync-gateway

COPY entrypoint.sh /tmp/entrypoint.sh
RUN chmod +x /tmp/entrypoint.sh

COPY config.json /tmp/config.json

ENTRYPOINT ["/bin/bash", "/tmp/entrypoint.sh"]
