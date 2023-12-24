## Dockerで環境構築
- イメージ作成
```bash
docker build . -t python_image
```
- コンテナ作成
```bash
docker run -it -d --name python_container python_image
```
- コンテナへ入る
```bash
docker exec -it python_container bash
```
