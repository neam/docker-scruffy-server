# docker-scruffy-server

[scruffy-server](https://github.com/wernight/scruffy-server) in docker.

## Usage

```sh
# either run in foreground (ctrl-c exits the server)
docker run -it -p 8080:8080 --rm neam/scruffy-server

# or in background (server keeps running until specifically killed)
docker logs -f $(docker run -d -p 8080:8080 neam/scruffy-server)
```

Visit http://ip-of-your-docker-host:8080 in your browser
