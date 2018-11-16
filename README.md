## 运行

```bash
docker run -d --name ss-many --restart always \
    --network host \
    -e NODE_ID=$NODE_ID \
    -e MYSQL_HOST=$MYSQL_HOST \
    -e MYSQL_PORT=$MYSQL_PORT \
    -e MYSQL_USER=$MYSQL_USER \
    -e MYSQL_PASS=$MYSQL_PASS \
    -e MYSQL_DB=$MYSQL_DB \
    serenader/ss-manyuser-docker
```
