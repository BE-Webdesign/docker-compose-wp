# Start Up

Copy `.env-example` to a new `.env` file and change `DOCKER_DEV_DOMAIN` to the
domain you want, and add it to your hosts file for localhost. By default it will
be `project.test`. Navigate to the root directory and run:

```
docker-compose up -d
```

This will start up Docker in detached mode and will set up all the images needed
to run WordPress. After the containers are up. You can navigate to what you set
for `DOCKER_DEV_DOMAIN` and install WordPress. From there you can use the themes
and plugins directories to keep track of project files.
