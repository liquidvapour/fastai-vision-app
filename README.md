# fastai-vision-app


Production ready starter pack for creating fast responsive Web App for Fast.AI Image models using Starlette.io framework with Uvicorn ASGI server.

Everything packaged in docker with requirement.txt, so you can push it to any docker hosted cloud service. Enjoy :)

Few dockers hosted services where this starter pack will work =>


* https://render.com
* https://zeit.co/now
* https://azure.microsoft.com/en-us/services/app-service/containers/
* https://getcarina.com/
* https://sloppy.io/en/
* https://giantswarm.io
* https://aws.amazon.com/ecs/
* https://cloud.google.com/cloud-build/docs/
* https://www.digitalocean.com/products/one-click-apps/docker/


## Useful commands

```
docker build .
```

build the container


```
docker run -p 8080:8080 -it [IMAGE] /bin/bash
```

Start container in interactive mode

```
docker run -p 8080:8080  -v d:\users\ra-el\Source\fastai\fastai-vision-app\app:/app -it f10c /bin/bash
```

Share the code from the host
