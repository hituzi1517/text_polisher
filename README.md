# 文章整形ツール

GitHub Pages向けの文章整形Webアプリです。

## 小説整形
- 地の文を全角1字下げ
- 「」『』などで始まる会話文は字下げしない
- 段落間に空行を1行入れる
- ただし「」や『』で始まる会話文が連続する場合は、その間に空行を入れない
- 三点リーダーを「……」へ統一
- ダッシュを「――」へ統一

## GitHub Pages
`index.html` と `.nojekyll` をリポジトリ直下へ置き、
Settings → Pages → Deploy from a branch → main / (root) を選択してください。
