# Julian I. Kamil / Jekyll

## Build and deployment steps

* Run cors-anywhere

** Run cors-anywhere directly

``` bash
PORT=1080 nohup nodejs server.js &
```

** Run cors-anywhere in a Docker container

``` bash
cd $WORKSPACE_DIR/dc-cors-anywhere
docker-compose up -d
```

* Run jekyll to build the site

``` bash
    bundle exec jekyll build
```

* Run jekyll to serve the site

``` bash
    bundle exec jekyll serve --host=0.0.0.0
```
