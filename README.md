# module（共通部品）

## カード（スライダー付）

- 親（card）の中に、子（card**wrap、card**photo_frame）を入れ子したタイプ。
- 子（card__photo_frame）はposition: absolute;で位置調整。
- スライダーはまだ未実装。
- positionを使ってるので、擬似要素での実現に変更。やり直し。

## イメージ画像

## portfolio url:

- https://css-md-0012.wtb.cfbx.jp/

## module(共通部品)使い方

-
-

## 注意事項
- positionは使い方を間違えると表示崩れの原因にもなるので、あくまでも最終手段として使うようにした方が良い！
- 


## 参考にしたサイト
- 擬似要素を使って画像と背景色を重ねる方法
- https://engineer.syutokoike.com/blog/css/128/
-

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> card をコピペ。

## 更新履歴

- 2022/3/1 スライダー未搭載分が完成。
- 2022/2/28 初版 一応、sp、tb、pc できたが、中央寄せが必要。改修中。

## 環境・使い方

- ダウンロードしたフォルダを開く
- ターミナルを開き、 npm i とコマンドを入力
- node_modules と package-lock.json が生成されるのを確認する
- 「 npx gulp 」とコマンドを入力すると動き出します
  å
