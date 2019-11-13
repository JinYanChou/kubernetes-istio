FROM redis:5.0.6-alpine

EXPOSE 6379 6379
COPY rediscluster.conf /etc/redis/rediscluster.conf
ENTRYPOINT redis-server /etc/redis/rediscluster.conf