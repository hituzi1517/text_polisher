# 文章整形ツール

GitHub Pages向けの文章整形Webアプリです。

## 小説整形
- 地の文を全角1字下げ
- 「」『』などで始まる会話文は字下げしない
- 連続空行を1行に整理
- 三点リーダーを「……」へ統一
- ダッシュを「――」へ統一
- 行末の余計な空白を削除
- 任意で段落間に空行を1行入れてWeb小説風に変換

## GitHub Pages
`index.html` と `.nojekyll` をリポジトリ直下へ置き、
Settings → Pages → Deploy from a branch → main / (root) を選択してください。
