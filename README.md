# Quick Demo (Development)

## Hugo
### Prerequisites:
- Hugo

### Run server
Launch command from folder:
```console
$ hugo server
```

## Docker
### Prerequisites:
- Docker

### Run server
Launch command from folder:
```console
$ docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:0.54.0 server
```

---
Website is available at http://localhost:1313
