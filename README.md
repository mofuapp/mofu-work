# もふぱう お仕事記録

ゆるかわいいお仕事時間トラッカー（PWA）

## 使い方

1. `index.html` をブラウザで開く、またはローカルサーバーで配信
2. 「はじめる」でタイマースタート →「作業終了」で記録
3. 記録タブでカレンダーの肉球スタンプを確認

## ローカルで試す

```bash
python3 -m http.server 8765
```

http://localhost:8765/index.html を開く

## ファイル構成

- `index.html` — アプリ本体
- `dog-illust.png` — 犬イラスト
- `paw-mark.png` — 肉球マーク
- `manifest.json` / `sw.js` — PWA 設定
