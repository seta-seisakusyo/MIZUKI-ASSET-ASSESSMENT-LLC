# みずきアセットアセスメント合同会社 - コーポレートサイト

みずきアセットアセスメント合同会社の公式ウェブサイトです。
クリニック不動産の管理・コンサルティング・資産価値評価を専門としています。

## サイトURL

https://mizuki-clinic.online

## 技術構成

- **HTML / CSS / JavaScript** によるシングルページ構成
- **Google Fonts**（Noto Sans JP / Noto Serif JP）
- **GitHub Pages** でホスティング
- **カスタムドメイン**（`mizuki-clinic.online`）

## ファイル構成

```
├── index.html     # メインページ（HTML・CSSを含む）
├── 404.html       # 404エラーページ
├── main.js        # JavaScript（アニメーション・メニュー）
├── icon.png       # ロゴ画像 / Apple Touch Icon
├── favicon.ico    # ファビコン
├── CNAME          # GitHub Pages カスタムドメイン設定
├── robots.txt     # クローラー制御
├── sitemap.xml    # サイトマップ
└── README.md      # このファイル
```

## ページ構成

| セクション | 内容 |
|---|---|
| ヘッダー | ロゴ・ナビゲーション（スティッキー） |
| ヒーロー | メインビジュアル・キャッチコピー |
| サービス | クリニック不動産管理 / 医療不動産コンサルティング / 資産価値評価 |
| 特徴 | 医療不動産専門 / 長期的資産管理 / 信頼と継続性 |
| 会社概要 | 会社名・所在地・代表社員・設立日・事業内容 |
| お問い合わせ | メールアドレス・電話番号 |

## 機能

- レスポンシブデザイン（モバイル対応・ハンバーガーメニュー）
- スクロール連動フェードインアニメーション（Intersection Observer API）
- スムーススクロールナビゲーション
- SEO対応（OGP / Twitter Card / JSON-LD構造化データ / canonical / sitemap）
- アクセシビリティ対応（スキップリンク / ARIA属性 / セマンティックHTML）
- セキュリティ対策（CSP / Referrer-Policy）

## ローカルでの確認

静的HTMLファイルのため、`index.html` をブラウザで直接開くか、任意のローカルサーバーで配信してください。

```bash
# 例: Python
python -m http.server 8000

# 例: Node.js (npx)
npx serve .
```
