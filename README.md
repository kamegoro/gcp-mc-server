# gcp-mc-server

GCP server management with terraform.

terraform 自動整形

```
$ terraform fmt
```

`discord.py`

Python 3.11 以上が必要です。Discord Developer Portal で Bot の **Message Content Intent** を有効にしてください。

```sh
$ python3 -m pip install -r requirements.txt
$ nohup python3 discordbot.py &
```

依存ライブラリを追加・更新する場合は `requirements.in` を編集し、ロックファイル `requirements.txt` を再生成します。

```sh
$ uv pip compile --universal --python-version 3.11 requirements.in -o requirements.txt
```
