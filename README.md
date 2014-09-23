# Dockerfile for sickbeard

# Build instructions

* Build: `docker -t build .`
* Run: `docker run -d --name="sickbeard_app" -p 8081:8081 -v /data:/mnt/media/TV sickbeard`
