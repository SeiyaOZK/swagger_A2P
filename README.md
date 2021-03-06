# The A2P & Bots Gateway

## 内容
- https://witlab-jp.wit-software.com/docsify/#/README
の仕様書をSwaggerベースで落とし込みます。
- バイトくん達の専用リポジトリ
- Swagger 3.0 OPEN APIで作成
- Git管理はGitHub

## 環境構築

### Docker for mac のインストール
https://store.docker.com/editions/community/docker-ce-desktop-mac

（個人の環境に応じてファイルシェアリングの設定を適宜設定してください）

### Gitからclone
`https://github.com/honma12345/swagger_A2P.git`

認証情報は管理者に問い合わせてください。

### ローカル環境でDocker立ち上げ

### docker-compose.ymlがあるswaggerディレクトリまでいく
```
$ docker-compose up
```
 - http://localhost:8001 を叩く。

## 参考一覧
### Swaggerの記法まとめ
https://qiita.com/rllllho/items/53a0023b32f4c0f8eabb#paths
### OpenAPI (Swagger) 超入門
https://qiita.com/teinen_qiita/items/e440ca7b1b52ec918f1b
### サンプルSwagger
https://app.swaggerhub.com/apis/GSMA/GSMA-MaaP-API/1.0.0-oas3#/
### 公式サイト
https://swagger.io/specification/#dataTypeFormat