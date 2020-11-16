# ci-docker-template
Docker上に構築済みのCodeIgniter環境

## How To Use

```
cd path-to-project
docker-compose up -d
docker-compose exec app bash
cd path-to-project && composer install
```

その後ブラウザで [http://0.0.0.0](http://0.0.0.0) を開く
