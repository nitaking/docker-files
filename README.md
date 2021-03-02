# About
docker files

# Container

- common-mysql: mysq@5.7
- common-redis: redis@4.0.9-alpine
- common-mongo: mongo@3.7.5
- 
# Script

Script | 説明
--- | ---
docker-compose up -d | 全コンテナ起動
docker-compose down | 全コンテナ停止

Script | 説明 | ex
--- | --- | ---
docker-compose up -d `<container-name>` | 個別コンテナ起動 | docker-compose up -d common-mysql<br>

