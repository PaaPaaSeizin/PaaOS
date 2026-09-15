# PaaOS
Chromium ブラウザだけで動く、ファイルシステム統合型の OS 風インターフェース。

## ※このリポジトリでOS本体のリリース等は行っていません！
公式サイトよりダウンロードください！

## インストール

### 動作環境

- Chromium 系ブラウザ（Chrome / Edge / Brave / Arc）
- File System Access API が有効であること（v86 以降）
- HTTPS または localhost で開くこと

### 手順

1. [公式サイト](https://paapaaseizin.github.io/PaaOS) から最新の PaaOS をダウンロード
2. 任意のフォルダに保存
3. ブラウザで `os.html` を開く
4. フォルダアクセスを許可 → 起動完了

## 技術スタック

| 領域 | 使用技術 |
|---|---|
| ファイルアクセス | File System Access API + IndexedDB |
| アプリ実行 | iframe + Blob URL |
| ZIP 圧縮 | JSZip |
| アニメーション | CSS transitions + 一部 GSAP |
| スクリーンショット | html2canvas |

## 注意事項

> [!WARNING]
> PaaOS は個人開発による実験的プロジェクトです。重要なファイルを保存する場所として使用しないでください。モジュール（`.modpaa`）は信頼できるもののみインストールしてください。

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照
