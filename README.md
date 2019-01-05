## Summary
Nuxt + Django REST Framework + MySQL

## Install
### 1. 必要なpackageをインストール
```
$ cd ./frontend/frontend
$ docker run --rm -it -v "$(pwd):/usr/src" node:8.11.1 bash 
> $ npm install
```

### 2. コンテナの起動
```
$ docker-compose build
$ docker-compose up db

---
End of list of non-natively partitioned tables
---
control + C

$ docker-compose up -d
```

### 3. 確認
- frontend [http://localhost:3000](http://localhost:3000)
- backend [http://localhost:8000](http://localhost:8000)
