FROM redis:5.0.6-alpine

EXPOSE 6379 6379
ADD rediscluster.conf /root/rediscluster.conf
ADD entrypoint.sh /root/entrypoint.sh
ENTRYPOINT ["sh","/root/entrypoint.sh", "&"]