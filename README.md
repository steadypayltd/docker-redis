# Redis

This is a small [Redis](https://redis.io) image built on [Alpine Linux](http://alpinelinux.org/) intended to run as a docker container on orchestration platforms such as Kubernetes.

This image will bootstrap redis container with specified role base on environment variable.

Credit should go to [@smileisak](https://github.com/smileisak) for his work on the original image. The image has been tweaked by adding few security patches.