FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
RUN "echo test"
ENTRYPOINT ["/entrypoint.sh"]
