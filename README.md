# 🟢 Apex-Launcher

**A modern, lightweight Minecraft Web Launcher.**

Apex-Launcher は、Minecraftのブラウザ版ゲームやクライアントをまとめて管理・起動できる、多機能Webランチャーです。

クライアントの選択からスキン管理、マルチプレイサーバーの確認、ゲームファイルのダウンロードまで、すべてを1つの画面から操作できます。

シンプルでスタイリッシュなダークテーマを採用し、PC・スマートフォンの両方に対応しています。

---

## ✨ Features

### 🎮 Game Launcher
- 複数のMinecraft HTMLゲームを選択して起動
- クライアントと通常ゲームを分けて表示
- WASM / WASM-GC / JS の種類を識別
- バージョン名の自動整形
- ファイル名による検索
- プレイヤー名の設定・保存
- ゲーム起動時のユーザー名同期

### 👤 Skin Manager
- 50種類のプリセットスキン
- Minecraftユーザー名からスキンを取得
- 自分のPNGスキンを複数追加
- スキンのダウンロード・削除
- 3Dスキンビューア搭載
- マウスやタッチ操作で3Dモデルを回転
- 64×32形式の旧スキンにも対応

### 🌐 Server List
- 17種類のマルチプレイサーバーを収録
- サーバーアドレスをワンクリックでコピー
- サーバーのオンライン人数を確認
- サーバーアイコンの取得
- サーバーの種類をタグで表示
- 対応バージョン情報の表示
- 自動ステータス更新機能
- 手動更新にも対応

### 📥 Download Manager
- 収録されたゲーム・クライアントを一覧表示
- ファイル名による検索
- HTMLファイルを個別にダウンロード
- ダウンロード可能なファイル数を表示

### ⚙️ Settings
- 日本語 / English の切り替え
- 6種類の背景テーマ
- オリジナル背景画像のアップロード
- 背景画像URLの設定
- 設定内容をブラウザに保存
- デバッグ情報の表示・コピー

---

## 🖥️ Interface

| Section | Description |
|---|---|
| Home | ランチャーのホーム画面 |
| Client | Minecraftクライアントの選択 |
| Skin Manager | スキンの管理・3D表示 |
| Server List | マルチプレイサーバー一覧 |
| Download | ゲームファイルのダウンロード |
| Settings | 言語・背景などの設定 |

---

## 🚀 Getting Started

### 1. Download

このリポジトリをダウンロード、または Clone します。

```bash
git clone <repository-url>
```

### 2. Open

`index.html` をブラウザで開きます。

ゲームファイルを正常に読み込むため、HTTPサーバー経由での利用を推奨します。

### 3. Play

1. Apex-Launcher を開く
2. プレイヤー名を入力
3. 起動したいゲームまたはクライアントを選択
4. **PLAY** ボタンを押す

これだけでゲームを起動できます！

---

## 🛠️ Technologies

Apex-Launcher は、以下のWeb技術を使用して構築されています。

- **HTML5** - UI構造
- **CSS3** - デザイン・レスポンシブ対応・3D表示
- **JavaScript** - ランチャー機能・各種処理
- **Canvas API** - スキンプレビュー・画像処理
- **WebSocket** - サーバーステータス取得
- **LocalStorage** - 設定・プロフィール・スキンの保存
- **SessionStorage** - セッション内のユーザー名同期

外部JavaScriptライブラリを必要としない、シングルHTML構成です。

---

## 📱 Compatibility

- Desktop Browsers
- Mobile Browsers
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Other modern browsers

一部の機能には、Canvas、WebSocket、Compression Streams API などに対応したブラウザが必要です。

---

## 💾 Data Storage

Apex-Launcher は、設定やユーザーデータの保存にブラウザのストレージを使用します。

保存される主なデータ：

- プレイヤー名
- 言語設定
- 背景設定
- 追加したマイスキン
- サーバー自動更新設定
- ゲームプロフィール関連データ

これらのデータは基本的にブラウザ内に保存されます。

ブラウザのデータ削除や別のブラウザへの移行によって、保存内容が失われる場合があります。

---

## ⚠️ Notes

- ゲームの起動には、対応するHTMLファイルが必要です。
- `index.html` とゲームファイルは、相対パスが変わらないように配置してください。
- スキン取得には外部サービス Minotar を使用します。
- サーバーステータスの取得には、各サーバーのWebSocket接続を使用します。
- サーバーの状態や対応バージョンは変更される場合があります。
- すべてのサーバーへの接続や動作を保証するものではありません。

---

## 💚 Apex-Launcher

**One Launcher. Multiple Experiences.**

Enjoy Minecraft your way.

