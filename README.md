# ok_server

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