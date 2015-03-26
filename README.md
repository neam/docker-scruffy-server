# docker-scruffy-server

[scruffy-server](https://github.com/wernight/scruffy-server) in docker.

## Usage

```sh
docker logs -f $(docker run -d -p 8080:8080 neam/scruffy-server)
```

Visit http://ip-of-your-docker-host:8080 in your browser
