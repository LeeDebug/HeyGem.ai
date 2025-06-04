## 启动命令（每次更新代码也要重启）

```bash
$ cd deploy
# 启动 hey-gem (重命名)
docker compose -p hey-gem -f docker-compose.yml down
docker compose -p hey-gem -f docker-compose.yml up -d
```
