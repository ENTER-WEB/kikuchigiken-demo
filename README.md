# 株式会社 菊池技研 — Demo Website

匠の技と真心で、よいえをカタチに。

KIKUCHI GIKEN のデモサイト（限定公開）。

## ファイル構成
```
kikuchigiken-demo/
├── index.html        # トップページ（認証付き）
├── sitemap.html      # サイトマップ（認証付き）
├── robots.txt        # 検索エンジン除外設定
├── README.md
└── images/           # 画像 15枚
```

## アクセス制限について
- すべてのページにクライアントサイドのパスワード認証を実装
- noindex/nofollow による検索エンジン除外
- robots.txt によるクロール拒否

## パスワード変更方法
`index.html` と `sitemap.html` の最下部にある以下の行を編集：
```js
const KG_PASSWORD = "kikuchi2024";
```
両ファイルで同じ値にしてください。
