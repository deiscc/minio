FROM minio/minio:RELEASE.2018-12-06T01-27-43Z

ENV MINIO_DATA_DIR /var/lib/minio/data
ENV MINIO_CONFIG_DIR /var/lib/minio/config

COPY . /

VOLUME "/var/lib/minio/data"

CMD ["/bin/boot"]
