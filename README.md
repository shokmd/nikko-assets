# Nikko Assets CDN

このリポジトリは、Nikkoプロジェクトの静的アセット（画像・動画）をjsDelivr CDN経由で配信するためのものです。

## CDN URL

```
https://cdn.jsdelivr.net/gh//nikko-assets@main/
```

## 使用方法

上記のCDN URLを環境変数に設定してください：

```bash
NUXT_PUBLIC_CDN_URL=https://cdn.jsdelivr.net/gh//nikko-assets@main/
```

## ファイル構成

- `image/` - 画像ファイル
- `video/` - 動画ファイル
- `favicon.png` - ファビコン
