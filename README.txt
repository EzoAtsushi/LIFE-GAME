進化を見守るくん（PWA一式）

フォルダ内容
- index.html
- manifest.json
- sw.js
- icon-*.png / apple-touch-icon.png / favicon-32.png

公開（GitHub Pages）
1) GitHubでリポジトリ作成
2) このzipの中身をリポジトリ直下にアップロード
3) GitHub → Settings → Pages → Deploy from a branch → main / (root) → Save
4) 表示されたURLをスマホで開く
5) iPhone: 共有 → ホーム画面に追加 / Android: メニュー → アプリをインストール

更新したのに反映されない時
- sw.js の CACHE_NAME を evolution-watch-v2 のように変えると更新されやすい
