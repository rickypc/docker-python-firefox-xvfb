Alpine Linux With Python 2.x, Firefox ESR, And Xvfb
===================================================

<a target="_blank" href="https://goo.gl/owFC4P">![Docker Stars](https://img.shields.io/docker/stars/rickypc/docker-python-firefox-xvfb.svg)</a>
<a target="_blank" href="https://goo.gl/owFC4P">![Docker Pulls](https://img.shields.io/docker/pulls/rickypc/docker-python-firefox-xvfb.svg)</a>
<a target="_blank" href="https://goo.gl/owFC4P">![Docker Size](https://img.shields.io/imagelayers/image-size/rickypc/docker-python-firefox-xvfb/latest.svg)</a>
<a target="_blank" href="https://goo.gl/owFC4P">![Docker Layers](https://img.shields.io/imagelayers/layers/rickypc/docker-python-firefox-xvfb/latest.svg)</a>
<a target="_blank" href="https://goo.gl/sXzgao">![Python](https://img.shields.io/pypi/pyversions/robotframework-extendedselenium2library.svg)</a>
<a target="_blank" href="http://goo.gl/LOMJeU">![License](https://img.shields.io/pypi/l/robotframework-extendedselenium2library.svg)</a>

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

License
-------
Copyright (c) 2015, 2016 Richard Huang.

This Dockerfile is free software, licensed under: [GNU Affero General Public License (AGPL-3.0)](http://www.gnu.org/licenses/agpl-3.0.en.html).
