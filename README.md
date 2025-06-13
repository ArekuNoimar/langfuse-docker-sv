## 注意

このリポジトリは、下記リンクのソースコードを、サーバー運用の為に改変したものです。

オリジナル版はこちらをご覧ください！
[langfuse](https://github.com/langfuse/langfuse)


```bash
# langfuseをホストするPCのIPアドレスに変更してください。
HOST_IP_ADDRESSES=127.0.0.1
```

```bash
cd ~/langfuse-docker-sv

sudo docker compose --env-file .env up -d
```