# pythonDocker

最新版のPython3環境が使えます。

## コマンドメモ

### 起動

```
docker compose up -d
```

### コンテナの中に入る

```
docker compose exec python3 bash
```

以降は下記のようなコマンドでPythonが実行できます

```
python opt/sample.py
```

### コンテナ終了

```
docker compose down
```