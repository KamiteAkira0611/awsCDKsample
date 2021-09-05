# awsCDKsample

## 事前準備

```
$ cp ./docker/infra/.env.sample ./docker/infra/.env
```

.env ファイルに自分の AWS アカウント情報を入力

## start

```
$ docker compose up
```

### 各種確認

```
$ aws sts get-caller-identity
$ cdk --version
$ node -v
$ python --version
```
