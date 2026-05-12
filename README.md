# kikuchigiken-demo (Public · Encrypted)

**株式会社 菊池技研** デモサイトの暗号化済み配信用リポジトリ。

⚠️ **このリポジトリのファイルは手動編集禁止**。`ENTER-WEB/kikuchigiken-site` の GitHub Actions が自動上書きします。

## 公開URL

https://enter-web.github.io/kikuchigiken-demo/

## アクセス方法

1. 上記URLにアクセス
2. 1Password共有リンクで取得したパスワードを入力
3. 「閲覧する」ボタンで復号化

## セキュリティ仕様

- HTML は staticrypt による AES-256 暗号化
- 平文ソースは Private repo (`ENTER-WEB/kikuchigiken-site`) で管理
- パスワードは 16文字ランダム英数字
- noindex / robots.txt で検索エンジン除外済

## 関連

- Source: [`ENTER-WEB/kikuchigiken-site`](https://github.com/ENTER-WEB/kikuchigiken-site) (Private)
- Runbook: [Demo Password Protect](https://enter-web.github.io/internal-shared/demo-password-protect.html)
