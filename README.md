# public-recustomer-api

## Setup
1. run this command
```
docker-compose up -d
```

2. access these link!

prism : http://localhost:3030

swagger-ui : http://localhost:3031

redoc : http://localhost:3032

## Devcontainer
DevContainerに接続することで、openapi向けvscode拡張機能を使うことができます

拡張機能は下記記事の拡張機能を追加しています
https://zenn.dev/s_t_pool/articles/954dfe51b950c18d08e9


## デプロイについて
現時点では自動デプロイ機構を用意していないので、下記の apidog プロジェクトの GUI を経由して、手動で `openapi.yml` をアップロードしてください。

apidog: https://apidog.com/apidoc/project-388017
