# GitHub Pages Fix Pack
これをリポジトリのルートにアップすると、
- `/rooms/` と `/bath/` にアクセスした時に、それぞれ `rooms.html` / `bath.html` へ自動リダイレクトされます。

## 使い方
1. `Add file` → `Upload files` で `rooms/index.html` と `bath/index.html` をアップロードして Commit。
2. 必要なら以下も確認：
   - `img/` フォルダがあり、画像名が **小文字 + .jpg** になっているか（例：`gaikan.jpg`）。
   - 動画が `video/IMG_4835.mov` として存在しているか（100MB以下）。
   - 反映されない時は、公開ページで **Shift + 再読み込み**。

## よくあるミス
- `Gaikan.JPG` や `.jpeg` のまま → HTMLの `gaikan.jpg` と一致せず読み込めない。
- `IMG_4835.mov` がアップされていない / サイズ超過で失敗 → ヒーローが静止画（poster）のまま。
- ルートに `index.html` が無い → サイト全体が 404。
