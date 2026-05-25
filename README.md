# tdmp_sample_page

東洋大学「観光デジタルメディア演習」で使用する Web サンプルページ集です。観光情報を Web 上で発信する基礎技術を実習形式で学ぶための教材として、GitHub Pages で公開しています。

## 公開 URL
- Step 0 (HTML のみ): https://Toyo-Univ-International-Tourism.github.io/tdmp_sample_page/sample0/
- Step 1 (HTML + CSS + JS): https://Toyo-Univ-International-Tourism.github.io/tdmp_sample_page/sample1/
- VR サンプル (シーン1): https://Toyo-Univ-International-Tourism.github.io/tdmp_sample_page/aframe_sample/scene1.html

## 収録サンプル

### `sample0/` — HTML のみの最小構成
素の HTML のみで構成した観光紹介ページの出発点。装飾もインタラクションもなし。`sample1/` と比較することで CSS / JS が果たす役割を学ぶ。

- HTML5 (セマンティックマークアップ)

### `sample1/` — HTML + CSS + JavaScript
`sample0/` に CSS による装飾と Vanilla JavaScript による DOM 操作 (ボタン操作で情報表示) を加えた完成版。

- HTML5 (セマンティックマークアップ)
- CSS3 (レイアウト・装飾)
- Vanilla JavaScript (DOM 操作)

### `aframe_sample/` — VR / 360° パノラマシーン
[A-Frame](https://aframe.org/) を用いた WebVR コンテンツの例。PC・スマートフォン・VR ヘッドセットのブラウザから 360 度画像を閲覧でき、シーン遷移やモーダル UI を実装。

- A-Frame v1.x (three.js ベースの WebVR/AR 宣言型フレームワーク)
- 360° パノラマ画像 (equirectangular 形式)
- カスタム JS コンポーネント (シーンリンク、情報モーダル)

## 動作環境
静的サイトのため追加インストール不要。Chrome / Safari / Firefox / Edge の最新版で動作確認済み。

## ライセンス・利用条件
- ソースコード (HTML / CSS / JS): MIT License
- 画像素材
  - `sample1/itsukushima.jpg`: Photo by Nicki Eliza Schinow on [Unsplash](https://unsplash.com/) (Unsplash License)
  - `aframe_sample/` 内の画像: 著者 (杉本興運) が東洋大学構内で撮影。教育・研究目的での参照は自由ですが、再配布・商用利用は事前にご連絡ください。
