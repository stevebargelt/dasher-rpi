# dasher-rpi

[![Build Status](https://travis-ci.org/stevebargelt/dasher-rpi.svg?branch=master)](https://travis-ci.org/stevebargelt/dasher-rpi)

## Docker Compose Example

```
version: '3.1'
services:
  dasher:
    image: stevebargelt/dasher-rpi
    volumes:
      - ./dasher/config:/usr/src/app/config
    network_mode: "host"
    restart: always
```

## To Find a new device

## 

