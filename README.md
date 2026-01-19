# HTML+CSS 管理画面システム

業務システムを想定した管理画面UIのフロントエンド実装です。  
HTML5とCSS3のみで構築し、JavaScriptは使用していません。

## 🌐 デモ

**GitHub Pages:** [https://xasukq.github.io/HTML-CSS-/](https://xasukq.github.io/HTML-CSS-/)

## 📸 スクリーンショット

| ログイン画面 | ダッシュボード |
|:---:|:---:|
| 専用レイアウト・グラデーション背景 | CSS Gridによる2カラムレイアウト |

| データ一覧 | 登録フォーム |
|:---:|:---:|
| テーブル・検索・ページネーション | 各種フォーム部品 |

## ✨ 特徴

- **Pure HTML+CSS** - JavaScriptを使用しない静的UI
- **レスポンシブデザイン** - デスクトップ / タブレット / スマートフォン対応
- **CSS Grid & Flexbox** - モダンなレイアウト手法
- **CSS変数** - カラーパレットの一元管理
- **セマンティックHTML** - アクセシビリティを考慮した構造

## 📁 ファイル構成

```
HTML-CSS-/
├── index.html          # トップ画面（ダッシュボード）
├── login.html          # ログイン画面
├── list.html           # データ一覧画面
├── detail.html         # データ詳細画面
├── form.html           # データ登録/編集画面
├── error.html          # エラー画面
├── css/
│   ├── common.css      # リセット・CSS変数・基本スタイル
│   ├── layout.css      # ヘッダー・サイドバー・フッター
│   ├── components.css  # ボタン・カード・テーブル等
│   ├── pages.css       # 各画面固有のスタイル
│   └── responsive.css  # メディアクエリ
└── img/                # 画像（今回は未使用）
```

## 🖥️ 画面一覧

| 画面 | ファイル | 説明 |
|------|----------|------|
| ログイン | `login.html` | 専用レイアウト、認証フォームUI |
| トップ | `index.html` | ダッシュボード、サマリーカード |
| 一覧 | `list.html` | データテーブル、検索、ページネーション |
| 詳細 | `detail.html` | データ詳細表示（dl/dt/dd形式） |
| 登録/編集 | `form.html` | 各種フォーム部品 |
| エラー | `error.html` | エラー表示UI |

## 🛠️ 使用技術

### フロントエンド
- HTML5（セマンティックタグ）
- CSS3（Grid, Flexbox, 変数, メディアクエリ）

### 外部リソース（CDN）
- [Font Awesome 6.5.1](https://fontawesome.com/) - アイコン
- [Google Fonts - Noto Sans JP](https://fonts.google.com/noto/specimen/Noto+Sans+JP) - 日本語フォント

## 📐 レスポンシブ対応

| ブレークポイント | 対象 | 主な変更 |
|------------------|------|----------|
| 1024px以上 | デスクトップ | 通常表示 |
| 768px - 1023px | タブレット | サイドバー幅縮小 |
| 767px以下 | スマートフォン | サイドバー非表示、1カラム |

## 🎨 カラーパレット

| 変数名 | 色 | 用途 |
|--------|-----|------|
| `--primary` | #2B579A | メインカラー |
| `--primary-dark` | #1E3A5F | ホバー時 |
| `--success` | #28A745 | 成功・有効 |
| `--danger` | #DC3545 | 危険・エラー |
| `--warning` | #FFC107 | 警告 |

## 📝 CSS設計

### ファイル分割の考え方

```
common.css      → 全体の土台（変数、リセット）
    ↓
layout.css      → ページ構造（Grid、ヘッダー、サイドバー）
    ↓
components.css  → 再利用可能なパーツ（ボタン、カード、テーブル）
    ↓
pages.css       → 画面固有のスタイル（ログイン、詳細、フォーム）
    ↓
responsive.css  → メディアクエリ（上書き）
```

### 読み込み順序

```html





```

## 🚀 ローカルで実行

### 方法1: VS Code + Live Server（推奨）

1. [VS Code](https://code.visualstudio.com/)をインストール
2. 拡張機能「Live Server」をインストール
3. プロジェクトフォルダを開く
4. `index.html`を右クリック →「Open with Live Server」

### 方法2: ブラウザで直接開く

`index.html`をダブルクリックしてブラウザで開く

## 📚 学習ポイント

このプロジェクトで学べる内容：

- [x] CSS Gridによるレイアウト構築
- [x] Flexboxによる要素配置
- [x] CSS変数を使ったカラー管理
- [x] レスポンシブデザインの実装
- [x] フォーム部品のスタイリング
- [x] Font Awesomeアイコンの活用
- [x] Google Fontsの読み込み
- [x] セマンティックHTMLの書き方

## 📄 関連ドキュメント

- 詳細設計書（Word形式）
- 構築手順書（Word形式）

## 👤 作成者

**ゆうた**  
インフラエンジニア / フルスタック志向

## 📜 ライセンス

このプロジェクトは学習目的で作成されています。
