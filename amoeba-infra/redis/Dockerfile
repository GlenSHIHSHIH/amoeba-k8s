FROM redis:6.2.5
COPY ./config/redis /usr/local/etc/redis

ENTRYPOINT ["redis-server", "/usr/local/etc/redis/redis.conf"]