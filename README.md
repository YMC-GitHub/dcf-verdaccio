# dcf-verdacci

setup npm private registry in docker

## prepare

- docker
- docker-compose

## setup

```bash
# speed up git clone in china
GC_PROXY="https://ghproxy.com/"
GC_URL="https://github.com/YMC-GitHub/dcf-verdacci.git"
GC_URL="${GC_PROXY}${GC_URL}"
git clone -b main "$GC_URL"
```

## start

```bash
docker-compose up -d
```

## usage
```bash

```

## Author

yemiancheng <ymc.github@gmail.com>

## License

MIT
