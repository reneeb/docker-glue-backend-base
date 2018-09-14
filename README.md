# docker-glue-backend-base

A small docker image with alpine and Mojolicious

I use this as a base for Glue dev environments.

```bash
# build current directory, wit latest commit as tag name
docker build  -t reneeb/alpinemojo:$(git rev-parse --short HEAD) .

# run the build with the latest commit as tag name
docker run -i -t reneeb/alpinemojo:$(git rev-parse --short HEAD)
```
