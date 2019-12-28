# ok_server
[![](https://images.microbadger.com/badges/image/tunnm/ok_server.svg)](https://microbadger.com/images/tunnm/ok_server "Get your own image badge on microbadger.com")[![](https://images.microbadger.com/badges/version/tunnm/ok_server.svg)](https://microbadger.com/images/tunnm/ok_server "Get your own version badge on microbadger.com")
Docker image, based on Nginx, return "OK" for any requests, with log format GELF



## Notes

This image has been included in several configurations:

    resolver 8.8.8.8;
    keepalive_timeout 65;
    client_max_body_size 1k;


## Usage

```bash
docker run tunnm/ok-server
```