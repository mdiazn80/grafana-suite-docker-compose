ARG MINIO_VERSION

FROM minio/minio:${MINIO_VERSION}

ENTRYPOINT sh -euc | mkdir -p /data/loki-data && mkdir -p /data/loki-ruler && minio server /data