# こちらはサービスを終了しました。


# QuakeViewer by USGS

このプロジェクトは、USGS Earthquake API を利用して地震情報をリアルタイムで取得し、地図上に表示するウェブアプリケーションです。通知機能や地震の詳細表示機能も備えています。

## デモ
以下のスクリーンショットをご覧ください。

![地震情報アプリのスクリーンショット](https://s10.aconvert.com/convert/p3r68-cdx67/atcyd-sfbrs.jpg)

## 主な機能

- **リアルタイム地震データ取得**: USGS Earthquake API を使って最新情報を取得します。
- **地図表示**: Leaflet.js を使用して地震情報を地図にプロットします。
- **カスタマイズされたマーカー**: マグニチュードに応じてマーカーの色とサイズを変更します。
- **通知機能**: 新しい地震情報があると通知バナーが表示されます。
- **詳細モーダルウィンドウ**: 地震情報をクリックすると詳細情報をポップアップ表示します。
- **レスポンシブデザイン**: モバイルやタブレットにも対応したデザイン。

## 使用技術

- **HTML5 / CSS3 / JavaScript**
- **[Leaflet.js](https://leafletjs.com/)**: 地図表示用
- **[USGS Earthquake API](https://earthquake.usgs.gov/fdsnws/event/1/)**: 地震データ取得用


## 使用方法

1. [こちら](https://hayato040404.github.io/QuakeViewer-by-USGS/) をブラウザで開きます。
2. 地図上に最新の地震情報が表示されます。
3. サイドバーの地震リストから詳細を確認できます。
4. 新しい地震が発生すると画面上部に通知が表示されます。

## ファイル構成
htmlにすべて格納されています。

```
.
├── index.html         # メインHTMLファイル
├── style.css          # カスタムCSS（必要に応じて追加）
├── script.js          # JavaScriptコード（必要に応じて分離）
├── screenshot.png     # アプリのスクリーンショット
```

## 今後の予定

- 地震の時系列アニメーション
- 特定の地域での地震フィルタリング機能
- 音声アラートの追加
- ダークモード対応

## 貢献方法(Β)

1. このリポジトリをフォークします。
2. 新しいブランチを作成します。
   ```bash
   git checkout -b feature/your-feature
   ```
3. コードをコミットします。
   ```bash
   git commit -m "Add your feature"
   ```
4. プッシュします。
   ```bash
   git push origin feature/your-feature
   ```
5. プルリクエストを送信します。

## ライセンス

このプロジェクトは [MIT License](LICENSE.md) の下で公開されています。

## 制限
動画配信についての制限は**一切ありません。**
