# cloudflared-proxy-dns

## Overview

A container to run a cloudflared DNS over HTTPs service.

## To run the service

```
docker run -p 53:53/udp -p 53:53/tcp -d raackley/cloudflared-proxy-dns
```

## References

This is based on [CloudFlare's Instructions](https://developers.cloudflare.com/1.1.1.1/dns-over-https/cloudflared-proxy/) to setup the service.
