# 漢字書き取りアプリ（静的ファイル版）

GitHub Pagesでそのまま公開できます。ビルド不要です。

## 構成

- `index.html`：アプリ本体
- `questions.json`：漢字問題
- `rewards.json`：ごほうび画像一覧
- `images/`：ごほうび画像

## GitHub Pages

リポジトリ直下へ、このフォルダの中身を階層を保ったまま配置します。

Settings → Pages → Deploy from a branch → `main` / `(root)`

## 更新

- 漢字の追加・修正：`questions.json`
- ごほうび画像：`images/` と `rewards.json`
- アプリ機能・見た目：`index.html`
