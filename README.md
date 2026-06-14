# いびつなシューティング / Distorted Shooting

## 概要

「いびつなシューティング」は、画面手前の左右2カ所に配置されたレーザーを使い、画面奥側に出現する黒丸ターゲットをできるだけ早く消すブラウザゲームです。

基本的なシューティングゲームで、素早く反応するほど高得点になります。ルールが追加されていくため、レベルが上がるにつれて、ターゲット位置だけでなくレーザーの色や速度を考える認知的な処理も得点に影響するようにしています。

“Distorted Shooting” is a browser game in which the player uses one of two lasers placed at the lower left and lower right of the screen to eliminate black targets that appear toward the top of the screen. Faster responses lead to better scores. As levels progress, additional rules require the player to process target position, laser color, and laser speed.

## ゲーム情報 / Game Information

- ゲームタイトル / Title: いびつなシューティング / Distorted Shooting
- 作成者 / Creator: komon
- ゲームID / Game ID: RG_komon_2026_01
- 実行形式 / Format: HTML / CSS / JavaScript
- 対応環境 / Environment: PC, smartphone, and tablet web browsers
- 推奨表示 / Recommended display: 横向き / Landscape orientation

## ファイル構成 / File Structure

```text
index.html    メイン画面 / Main page
game.html     ゲーム画面 / Game page
policy.html   利用条件画面 / Policy page
LICENSE.txt   利用条件・免責事項 / Terms and disclaimer
README.md     この説明ファイル / This description file
```

## 操作方法 / Controls

### PC

- 左レーザー / Left laser: F key
- 右レーザー / Right laser: J key

### Smartphone / Tablet

- 左右のレーザー部分をタッチして発射します。
- Tap the left or right laser area at the bottom of the screen.

## 言語切り替え / Language Switching

各HTMLファイルには言語切り替えボタンがあります。初期表示は日本語です。言語設定はブラウザのlocalStorageに保存され、ページ間で引き継がれます。

Each HTML file includes a language switch button. The default language is Japanese. The language setting is stored in the browser’s localStorage and is shared across pages.

## 利用条件 / Terms of Use

本ソフトウェアは、研究、教育、および試作目的で公開されています。医療機器として設計・認証されたものではありません。詳しい利用条件、禁止事項、免責事項については、`policy.html` および `LICENSE.txt` を確認してください。

This software is published for research, education, and prototype purposes. It is not designed or certified as a medical device. See `policy.html` and `LICENSE.txt` for detailed terms, prohibited actions, and disclaimers.
