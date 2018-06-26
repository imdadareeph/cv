# Demo
[DEMO-URL](http://www.imdadareeph.com/cv/)

Note: Hard-refresh the browser if components does not load first time.


# Screenshot
![alt text](http://i63.tinypic.com/212hiys.jpg "preview1")

# How to use?

Simply build the image using `$docker build -t imdadareeph/rhel7nodejs9:v2.0.0 .`

and run it with all needed parameter:

```console
$ docker run -d -p 8888:8888 imdadareeph/rhel7nodejs9:v2.0.0 
```

That's it.

## Templates and others

This image uses templates modified from free site.Credit goes to Creative CV - TemplateFlip

## Environment variables

This image uses following commands for configuration.

|docker commands     |Default value        |Description                                         |
|------------------------|---------------------|----------------------------------------------------|
|`Docker build`    |no default           |$docker build -t imdadareeph/rhel7nodejs9:v2.0.0 .|
|`Docker run`    |no default           |docker run -d -p 8888:8888 imdadareeph/rhel7nodejs9:v2.0.0            |



# Updates and updating

To update your setup simply pull the newest image version from docker hub and run it.


## Deprecated features

Instead of using imdadareeph/rhel7nodejs9 image, any light nodejs image can be used (e.g. node:alpine)

# License

Everything in [this repository](https://github.com/imdadareeph/imdadareeph.github.io) is published under [GPL-3](https://spdx.org/licenses/GPL-3.0).
