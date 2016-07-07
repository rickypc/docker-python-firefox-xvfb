Docker Installation
-------------------

Please see the [Docker installation documentation](https://docs.docker.com/installation/) for details

Run
---

You can run the image directly:
```bash
docker run --rm -ti rickypc/docker-python-firefox-xvfb /bin/bash
```

Usage
-----

Use like you would any other base image:
```bash
FROM rickypc/docker-python-firefox-xvfb:latest
COPY requirements.txt .
RUN apk add --no-cache py-pip && pip install -r requirements.txt
```
