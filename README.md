# Dockerfile for sickbeard

### This project has moved to https://github.com/ajclark/usenet

# Build instructions

* Build: `docker build -t sickbeard .`
* Run: `docker run -d --name=sickbeard_app --restart=always -v /data/warehouse/sickbeard:/data -v /mnt/media:/mnt/media -p 8081:8081 sickbeard`
