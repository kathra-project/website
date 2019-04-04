# Quick Demo (Development)

[![Netlify Status](https://api.netlify.com/api/v1/badges/9ac0d7b7-8ae9-43b3-bff9-d6b8355e2f16/deploy-status)](https://app.netlify.com/sites/stoic-carson-04c63b/deploys)

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
