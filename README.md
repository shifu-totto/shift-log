## blog is here -> https://shifu-totto.github.io/shift-log/

このブログはJekyllからHugoへ移行しました。

### ローカル起動

Hugo Extendedをインストールした環境では、プロジェクトのルートで次を実行します。

```powershell
hugo server -D
```

Dockerを使う場合は次を実行します。

```powershell
docker compose up
```

ブラウザで `http://localhost:1313/shift-log/` を開きます。記事は `content/posts/`、固定ページは `content/`、テンプレートは `layouts/` にあります。