playing with deepdream

```
docker pull kennydo/deepdream-docker

docker run \
--rm \
-it \
-p 8888:8888 \
-v /host/path/to/data:/data \
kennydo/deepdream-docker \
sudo \
jupyter \
notebook \
--port 8888 \
--ip 0.0.0.0 \
--no-browser
```
