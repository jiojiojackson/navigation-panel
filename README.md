# navigation-panel

シンプルな静的サイト（ホームページ + 他の HTML ページ）です。Vercel にデプロイ可能。

ファイル:

- `index.html` - ホームページ（ナビゲーション含む）
- `about.html` - About ページ（HTML）
- `contact.html` - Contact ページ（HTML）
- `styles/style.css` - スタイル
- `vercel.json` - Vercel 用の設定（クリーン URL を有効化）

クイックスタート（Vercel にデプロイする方法）:

1. GitHub にこのリポジトリをプッシュして、Vercel ダッシュボードからリポジトリをインポートするだけで動きます。

2. または Vercel CLI を使う場合（ローカルで動作確認→デプロイ）:

```bash
# ローカルで簡易サーバ起動（ルートで実行）
python3 -m http.server 3000
# ブラウザで http://localhost:3000 を開く

# Vercel CLI を使ってデプロイ
npm i -g vercel
vercel login
vercel --prod
```

注意: `vercel.json` の `cleanUrls` をオンにしているため、`/about` や `/contact` のようなクリーン URL でアクセスできます。

もし追加のページやカスタムドメインが必要なら、README を更新してサポートします.