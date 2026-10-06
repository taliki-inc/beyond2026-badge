# BEYOND2026 参加表明ジェネレーター

ソーシャルカンファレンス BEYOND2026（2026.10.30 Fri - 10.31 Sat / 京都）の参加表明画像を作るツール。

公開URL: https://taliki-inc.github.io/beyond2026-badge/

写真を選んで位置と大きさを合わせると、SNSシェア用の画像（PNG / 1080×1350）がダウンロードできる。
合成はすべてブラウザ内（Canvas）で完結し、選んだ写真はサーバーに送信されない。

## 構成

- `index.html` — 本体（HTML・CSS・JS を1ファイルに同梱）
- `assets/frame.png` — 枠デザイン
- `assets/overlay.png` — 写真より手前に重ねる要素（BEYONDロゴ等）

## 更新のしかた

このリポジトリは配信用。生成スクリプトを含む作業用の一式は
社内の `beyond-skill` リポジトリ `tools/参加表明ジェネレーター/` にある。
そちらで直してから `index.html` と `assets/` をコピーして push する。
