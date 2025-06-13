### 注意

このリポジトリは、下記リンクのソースコードを、サーバー運用の為に改変したものです。

オリジナル版はこちらをご覧ください！
[langfuse](https://github.com/langfuse/langfuse)

<br>

< 設定変更 >
```bash
# langfuseをホストするPCのIPアドレスに変更してください。
HOST_IP_ADDRESSES=127.0.0.1
```

< 起動 >
```bash
cd ~/langfuse-docker-sv

sudo docker compose --env-file .env up -d
```

< ファイヤーウォール設定変更 >
```bash
sudo ufw allow 3000/tcp # langfuse-web
sudo ufw allow 80/tcp # http
```