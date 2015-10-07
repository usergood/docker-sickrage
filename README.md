# docker SickGear

This is a Dockerfile to set up "SickGear" - (https://sickrage.tv/forums/)

Build from docker file

```
git clone git@github.com:usergood/docker-sickrage.git
cd docker-sickrage
docker build -t sickrage .
```

docker run --restart=always -d -h *your_host_name* -v /*your_config_location*:/config  -v /*your_videos_location*:/data -p 8081:8081 SickGear

