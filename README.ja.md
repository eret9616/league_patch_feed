# リーグ・オブ・レジェンド パッチノート RSS フィード

[English](README.md) · [简体中文](README.zh-CN.md) · **日本語** · [한국어](README.ko.md)

リーグ・オブ・レジェンドのパッチノートを配信する RSS フィードです。Vercel 上にデプロイされています。

## 機能

- リーグ・オブ・レジェンド公式のパッチノートを自動取得
- RSS フィードを生成
- 画像と詳細な説明に対応

## デプロイ

1. このリポジトリを Fork する
2. [Vercel](https://vercel.com) で自分のリポジトリをインポートする
3. デプロイが完了すると、RSS フィードの URL は次のようになります：`https://あなたのドメイン/api/rss`

## ローカル開発

```bash
# 依存関係をインストール
npm install

# ローカルで実行
npm run dev
```

## 技術スタック

- Node.js
- Axios
- Cheerio
- RSS
- Vercel Serverless Functions

## 注意事項

- リーグ・オブ・レジェンド公式サイトの利用規約を必ず遵守してください
- 頻繁なリクエストを避けるため、適切なリクエスト間隔を設定することをおすすめします
