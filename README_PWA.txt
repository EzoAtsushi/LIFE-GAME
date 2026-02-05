PWA用ファイル一式（LifeGame）

配置（index.htmlと同じフォルダに置く想定）
- index.html              (既存)
- manifest.webmanifest    (このフォルダに追加)
- sw.js                   (このフォルダに追加)
- icons/                  (このフォルダに追加)
  - icon-192.png
  - icon-512.png
  - maskable-192.png
  - maskable-512.png
  - apple-touch-icon.png
  - favicon-32.png
  - favicon-16.png

index.html に追記が必要なもの（この回答のあと、canvas側のHTMLにも反映済み）
- <link rel="manifest" href="manifest.webmanifest">
- アイコンlink（apple-touch-icon, favicon）
- service worker 登録コード（sw.js）

注意
- PWAは https 配信が必要です（GitHub PagesならOK）
- 反映確認は iOS Safari なら「共有」→「ホーム画面に追加」
