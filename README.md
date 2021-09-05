# awsCDKsample

公式チュートリアル
https://cdkworkshop.com/20-typescript/20-create-project.html

## 事前準備

```
$ cp ./docker/infra/.env.sample ./docker/infra/.env
```

.env ファイルに自分の AWS アカウント情報を入力

## start

```
$ docker compose up
```

`docker compose exec infra bash`にて作業

### 各種確認

```
$ aws sts get-caller-identity
$ cdk --version
$ node -v
$ python --version
```
