# Julian I. Kamil / Jekyll

## Build and deployment steps

* Run cors-anywhere

``` bash
PORT=1080 nohup nodejs server.js &
```

* Run jekyll to build the site

``` bash
    bundle exec jekyll build
```

* Run jekyll to serve the site

``` bash
    bundle exec jekyll serve --host=0.0.0.0
```
