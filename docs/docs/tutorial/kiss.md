# KISS
> Build and preview a site locally

Select two objects, enter edit mode, select a face on one obj, then a 
face on the other and press kiss.

```sh
$ cd docs
```
https://www.youtube.com/watch?v=H51zh25KGGY

## CLI help

```sh
$ make help
```
```
default: install
all: install build
h help:
install:
upgrade:
s serve:
b build:
d deploy:
```


## Serve docs

This will build the docs in memory (not to disk) and serve an auto-reloading server.

```sh
$ make serve
```

Then open in your browser:

- [localhost:8000](http://localhost:8000)


## Build docs

Build docs site to `site` directory. This is useful for a CI flow.

```sh
$ make build
```
