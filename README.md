# todo-app-nextjs
Next.jsで作成したToDoアプリ

## ローカル環境構築手順
```
# コンテナの起動
docker compose up -d

# フロントエンド接続
http://localhost:3001

```

## その他
```
# nextjsコンテナに入る
docker exec -it nextjs bash

# コンテナの停止とボリュームの削除
docker compose down --volumes
```