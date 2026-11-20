# Japanese with Daisy — website

GitHub Pagesで公開するサイト一式です。

## 中身
- `index.html` … サイト本体（Home / About me / Themes / Curriculum / Art gallery）
- `img/` … サイトで使っている写真とロゴ
- `gallery/` … 承認した生徒さんの作品を入れるフォルダ
- `gallery.json` … ギャラリーに載せる作品のリスト

## 設定（index.html の上のほう）
```js
window.SITE = {
  GA_ID: "",          // Google AnalyticsのID（例 "G-ABC123XYZ"）。空ならオフ
  INSTAGRAM_URL: ""   // InstagramのURL（例 "https://www.instagram.com/アカウント名/"）
};
```

## 作品をギャラリーに載せる方法
1. 承認した画像を `gallery/` に入れる（例 `gallery/2026-11-20_mia.jpg`）
2. `gallery.json` に1行ずつ追加する（新しいものを上に）
```json
[
  {"file": "gallery/2026-11-20_mia.jpg", "like": "Cherry blossoms along the river", "sign": "Mia · Brazil"}
]
```
3. GitHubに保存すると、数分でサイトに反映されます。

本人の許可がない名前・顔写真は載せないでください。
