# daily-news

## セットアップ

1. 暗号化キーを生成する

```bash
openssl rand -hex 32
```

2. `.env` ファイルを作成する

```bash
cp .env.example .env
```

3. `.env` に生成したキーを設定する

```
N8N_ENCRYPTION_KEY=生成したキーをここに貼り付け
```

4. n8n を起動する

```bash
docker compose up -d
```
