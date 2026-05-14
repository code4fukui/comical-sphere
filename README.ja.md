# comical-sphere

コミカルな画像のテクスチャを貼り付けた、3つのアニメーションする3D球体を描画するシンプルなWebアプリケーションです。すべての処理が単一のHTMLファイルで完結しており、3DレンダリングにはThree.jsを使用しています。

## デモ

https://code4fukui.github.io/comical-sphere/

## 機能

- 円軌道に沿って移動する、3つのアニメーションする3D球体を描画します。
- テクスチャには `img/20240724-comical{1,2,3}.jpg` を使用しています。
- パンやズームなどのインタラクティブなカメラ操作が可能です。
- 単一の `index.html` ファイルで完結しており、ビルドは不要です。
- [egxr.js](https://github.com/code4fukui/egxr.js) ライブラリを介して [Three.js](https://threejs.org/) を利用しています。

## 使い方

1.  **アプリケーションの実行:** WebGLとECMAScriptモジュールをサポートするモダンなWebブラウザで `index.html` を開きます。
2.  **カメラの操作:**
    -   **矢印キー:** カメラビューをパンします（左右および前後に移動）。
    -   **マウスホイール:** ズームイン・ズームアウトします。

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
