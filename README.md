# Impact Platform: Redis
[Docker](https://www.docker.com/) container for [Redis](http://redis.io/)

## Overview
A Redis database, exposes port `6379`.

## Docker-Compose Usage
```
redis:
    build: impactbot/impact-platform-redis
    ports:
        - "6379:6379"
```
