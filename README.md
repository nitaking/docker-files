# About
docker files

# Script

Script | 説明
--- | ---
docker-compose up -d | 全コンテナ起動
docker-compose down | 全コンテナ停止

Script | 説明 | ex
--- | --- | ---
docker-compose up -d `<container-name>` | 個別コンテナ起動 | docker-compose up -d common-mysql<br>

# Container

- common-mysql@5.7
- common-redis@4.0.9-alpine
- common-mongo@3.7.5
