# X Player Card Test

GitHub Pagesで旧 `twitter:card=player` が現在も機能するか確認するための最小テストです。

## 公開前

`index.html` の以下を置換してください。

- `YOUR_GITHUB_USERNAME`
- `YOUR_REPOSITORY`

例:

`https://walkingwifi28.github.io/x-player-card-test`

## GitHub Pages

Repository Settings → Pages → Deploy from a branch → `main` / `/ (root)` を選択。

公開後、トップURLをXへ投稿します。

## 判定

- player.html の A/B ボタンまでポスト内に出て押せる → HTML/JS Playerが生きている可能性が高い
- 動画だけ出る → streamのみ利用されている可能性
- 通常リンクカードだけ → Player Cardが一般向けにはレンダリングされていない可能性
