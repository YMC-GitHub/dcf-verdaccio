# dcf-verdaccio

setup npm private registry in docker

## prepare

- docker
- docker-compose

## setup

```bash
# speed up git clone in china
GC_PROXY="https://ghproxy.com/"
GC_URL="https://github.com/YMC-GitHub/dcf-verdaccio.git"
GC_URL="${GC_PROXY}${GC_URL}"
git clone -b main "$GC_URL"
```

## start

```bash
docker-compose up -d
```

## usage

[using verdaccio with npm]()

[manage npm registry url with nrm]()

## trouble
```bash
#Error: EACCES: permission denied, open '/verdaccio/conf/htpasswd'
#ls -ld services/verdaccio
#sudo chown -R 10001:65533 services/verdaccio
```

## Author

yemiancheng <ymc.github@gmail.com>

## License

MIT
