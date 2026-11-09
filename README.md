# 🟢 Apex-Launcher english

**A modern, lightweight Minecraft web launcher.**

Apex-Launcher is a feature-rich web-based launcher that allows you to manage and launch both browser-based versions of Minecraft and various game clients from a single interface.

From selecting clients and managing skins to checking multiplayer servers and downloading game files—everything can be handled from one screen.

It features a clean, stylish dark theme and is compatible with both PCs and smartphones. 
---

## ✨ Features

### 🎮 Game Launcher
- Select and launch various Minecraft HTML-based games
- Separate display for clients and standard games
- Identification of game types (WASM / WASM-GC / JS)
- Automatic formatting of version names
- Search by filename
- Set and save player names
- Username synchronization upon game launch

### 👤 Skin Manager
- 50 preset skins
- Retrieve skins using Minecraft usernames
- Add your own custom PNG skins
- Download or delete skins
- Built-in 3D skin viewer
- Rotate 3D models using mouse or touch controls
- Support for legacy 64×32 format skins

### 🌐 Server List
- Includes 17 multiplayer servers
- One-click server address copying
- View current online player counts
- Retrieve server icons
- Server type categorization via tags
- Display of compatible version information
- Automatic status updates
- Manual refresh option

### 📥 Download Manager
- List of available games and clients
- Search by filename
- Download individual HTML files
- Display of total downloadable file count

### ⚙️ Settings
- Language toggle (Japanese / English)
- 6 background themes
- Upload custom background images
- Set background images via URL
- Save settings to your browser
- View and copy debug information

---

## 🖥️ Interface

| Section | Description |
|---|---|
| Home | Launcher home screen |
| Client | Select Minecraft clients |
| Skin Manager | Manage and view skins in 3D |
| Server List | List of multiplayer servers |
| Download | Download game files |
| Settings | Configure language, background, etc. |

---

## 🚀 Getting Started

### 1. Download

Download or clone this repository. ```bash
git clone <repository-url>

### 2. Open

Open `index.html` in your web browser.

It is recommended to access the files via an HTTP server to ensure the game files load correctly.

### 3. Play

1. Open Apex-Launcher.
2. Enter your player name.
3. Select the game or client you wish to launch.
4. Click the **PLAY** button.

That’s all it takes to launch the game!

---

## 🛠️ Technologies

Apex-Launcher is built using the following web technologies:

- **HTML5** – UI structure
- **CSS3** – Design, responsive layout, and 3D rendering
- **JavaScript** – Launcher functionality and logic
- **Canvas API** – Skin previews and image processing
- **WebSocket** – Retrieving server status
- **LocalStorage** – Saving settings, profiles, and skins
- **SessionStorage** – Synchronizing the username within a session

It is a single-file HTML application that requires no external JavaScript libraries.

---

## 📱 Compatibility

- Desktop browsers
- Mobile browsers
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Other modern browsers

Certain features require a browser that supports the Canvas, WebSocket, and Compression Streams APIs.

---

## 💾 Data Storage

Apex-Launcher uses browser storage to save your settings and user data.

Data stored includes:

- Player name
- Language settings
- Background settings
- Custom skins you have added
- Server auto-update settings
- Game profile-related data

This data is stored locally within your browser.

Please note that clearing your browser data or switching to a different browser may result in the loss of your saved information.

---

## ⚠️ Notes

- External service "Minotar" is used to retrieve skins.
- WebSocket connections to individual servers are used to fetch server status.
- Server status and supported versions are subject to change. - Connection to or operation with all servers is not guaranteed.

---

## 💚 Apex-Launcher

**One Launcher. Multiple Experiences.**

Enjoy Minecraft your way.

---

# 🟢 Apex-Launcher japanese

**A modern, lightweight Minecraft Web Launcher.**

Apex-Launcher は、Minecraftのブラウザ版ゲームやクライアントをまとめて管理・起動できる、多機能Webランチャーです。

クライアントの選択からスキン管理、マルチプレイサーバーの確認、ゲームファイルのダウンロードまで、すべてを1つの画面から操作できます。

シンプルでスタイリッシュなダークテーマを採用し、PC・スマートフォンの両方に対応しています。

---

## ✨ Features

### 🎮 Apex-launcher
- 複数のMinecraft HTMLゲームを選択して起動
- クライアントと通常ゲームを分けて表示
- WASM / WASM-GC / JS の種類を識別
- バージョン名の自動整形
- ファイル名による検索
- プレイヤー名の設定・保存
- ゲーム起動時のユーザー名同期

### 👤 スキン管理
- 50種類のプリセットスキン
- Minecraftユーザー名からスキンを取得
- 自分のPNGスキンを複数追加
- スキンのダウンロード・削除
- 3Dスキンビューア搭載
- マウスやタッチ操作で3Dモデルを回転
- 64×32形式の旧スキンにも対応

### 🌐 サーバーリスト
- 17種類のマルチプレイサーバーを収録
- サーバーアドレスをワンクリックでコピー
- サーバーのオンライン人数を確認
- サーバーアイコンの取得
- サーバーの種類をタグで表示
- 対応バージョン情報の表示
- 自動ステータス更新機能
- 手動更新にも対応

### 📥 ダウンロード
- 収録されたゲーム・クライアントを一覧表示
- ファイル名による検索
- HTMLファイルを個別にダウンロード
- ダウンロード可能なファイル数を表示

### ⚙️ 設定
- 日本語 / English の切り替え
- 6種類の背景テーマ
- オリジナル背景画像のアップロード
- 背景画像URLの設定
- 設定内容をブラウザに保存
- デバッグ情報の表示・コピー

---

## 🖥️ インターフェース

| セクション | 説明 |
|---|---|
| Home | ランチャーのホーム画面 |
| Client | Minecraftクライアントの選択 |
| Skin Manager | スキンの管理・3D表示 |
| Server List | マルチプレイサーバー一覧 |
| Download | ゲームファイルのダウンロード |
| Settings | 言語・背景などの設定 |

---

## 🚀 始める

### 1. ダウンロード

このリポジトリをダウンロード、または Clone します。

```bash
git clone <repository-url>
```

### 2. 開く

`index.html` をブラウザで開きます。

ゲームファイルを正常に読み込むため、HTTPサーバー経由での利用を推奨します。

### 3. プレイ

1. Apex-Launcher を開く
2. プレイヤー名を入力
3. 起動したいゲームまたはクライアントを選択
4. **プレイ** ボタンを押す

これだけでゲームを起動できます！

---

## 🛠️ テクノロジー

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

## 📱 コンパチビリティ

- Desktop Browsers
- Mobile Browsers
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Other modern browsers

一部の機能には、Canvas、WebSocket、Compression Streams API などに対応したブラウザが必要です。

---

## 💾 データストレージ

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

## ⚠️ メモ

- スキン取得には外部サービス Minotar を使用します。
- サーバーステータスの取得には、各サーバーのWebSocket接続を使用します。
- サーバーの状態や対応バージョンは変更される場合があります。
- すべてのサーバーへの接続や動作を保証するものではありません。

---

## 💚 Apex-Launcher

**一つのランチャーで様々な体験を**

自分らしい方法でマインクラフトを楽しもう！
