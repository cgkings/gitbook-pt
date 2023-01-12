# Transmission

Docker版Tr--helloz修改版

```
docker run -d --name="transmission" \
  -p 51413:51413 \
  -p 51413:51413/udp \
  -p 9091:9091 \
  -e USERNAME=admin \
  -e PASSWORD=adminadmin \
  -v /data/downloads:/home/tr/downloads \
  -v /data/transmission:/root/.config/transmission-daemon \
  --restart=always \
  helloz/transmission
```
