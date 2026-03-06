# 🌸 Bloom Routine

朝の準備と日々の習慣をサポートするPWAアプリ。  
中学生〜高校生向けに設計されたルーティン管理ツールです。

## ✨ 機能

- **今日のルーティン** — 習慣をチェックするたびにXPがたまる
- **朝の準備タイム** — リアルタイム時計 + 優先度付きタスクリスト
- **妥協アレンジ集** — 時間がないときの賢いヘアスタイル選択
- **タスクタイマー** — 「5分でどこまでできるか」を体感
- **XP・レベル・バッジ** — 続けることが楽しくなる記録システム

## 🚀 使い方（GitHub Pages）

1. このリポジトリを Fork または Clone
2. GitHub の Settings → Pages → `main` ブランチの `/ (root)` を選択
3. 公開されたURLをスマホで開き、「ホーム画面に追加」でインストール完了

## 📁 ファイル構成

```
bloom-routine/
├── index.html          # メインアプリ
├── manifest.json       # PWA設定
├── sw.js               # Service Worker（オフライン対応）
└── icons/
    ├── icon.svg        # オリジナルSVGアイコン
    ├── icon-192.png    # PWAアイコン
    ├── icon-512.png    # PWAアイコン（大）
    ├── apple-touch-icon.png  # iOS用
    ├── icon-32.png     # ファビコン
    └── icon-16.png     # ファビコン（小）
```

## 🛠 ローカルで動かす

```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx serve .
```

ブラウザで `http://localhost:8000` を開く。

> **Note:** Service Workerはローカルサーバー環境(`localhost`)でのみ正常に動作します。`file://`プロトコルでは動作しません。

## 📱 PWAインストール方法

### iPhone / iPad (Safari)
1. Safariでアプリのページを開く
2. 共有ボタン（□↑）→「ホーム画面に追加」

### Android (Chrome)
1. Chromeでアプリのページを開く
2. アドレスバー右の「インストール」アイコン、または メニュー → 「ホーム画面に追加」

---

Made with 💜 — Small steps, big blooms.
