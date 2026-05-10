# 株式会社 菊池技研 — Demo Website

匠の技と真心で、よいえをカタチに。

KIKUCHI GIKEN のデモサイト。山形の自然と職人の技を伝える、和の意匠を取り入れたコーポレートサイトです。

## ファイル構成

```
kikuchigiken-demo/
├── index.html          # トップページ
├── sitemap.html        # サイトマップページ
└── images/             # 画像アセット (15枚)
    ├── 01_main_visual_wooden_living.webp
    ├── 02_craftsmanship_carpenter_hands.webp
    ├── 03_local_wood_yamagata_forest.webp
    ├── 04_family_warm_living.webp
    ├── 05_regional_landscape_city_mountains.webp
    ├── 06_residential_house_exterior.webp
    ├── 07_public_architecture_building.webp
    ├── 08_civil_engineering_road.webp
    ├── 09_wooden_interior_lounge.webp
    ├── 10_house_detail_greenery.webp
    ├── 11_garden_deck_house.webp
    ├── 12_courtyard_bench_architecture.webp
    ├── 13_joinery_craft_detail.webp
    ├── 14_yamagata_mountain_landscape.webp
    └── 15_recruit_staff_portrait.webp
```

## ページ構成

### `index.html` — トップページ
- ヘッダー（ロゴ／ナビゲーション／お問い合わせCTA）
- ヒーローセクション（メインビジュアル + キャッチコピー）
- 私たちの強み（4つの力：匠の技 / 県産木材 / 真心 / 地域貢献）
- 事業内容（住宅事業 / 公共建築 / 土木事業 / 不動産・その他）
- 施工実績（4枚スライダー）
- 菊池技研について
- お知らせ ／ 採用情報
- お問い合わせ帯
- フッター

### `sitemap.html` — サイトマップ
8カテゴリの全ページ階層を2カラム構成で一覧表示

## デザイン仕様

| 項目 | 値 |
|---|---|
| 和文タイトル | Shippori Mincho B1 |
| 和文本文 | Noto Sans JP |
| 欧文 | Cormorant Garamond |
| 主色（深緑） | `#2d4a36` |
| 背景（クリーム） | `#f8f4ed` |
| アクセント（金茶） | `#b89968` |

## ローカルでの確認方法

```bash
# 任意の方法でローカルサーバーを起動
python3 -m http.server 8000
# → ブラウザで http://localhost:8000 にアクセス
```

または `index.html` を直接ブラウザで開いてもOKです（画像は同階層の `images/` フォルダから読み込まれます）。

## ライセンス

社内デモ用途
