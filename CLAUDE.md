# WCMs 開発メモ（AI向け）

- サークル用アプリ。UI・コメント・説明はすべて日本語
- 構成は兄弟アプリ `../pinq-editor` と同じ：HTML＋素のJavaScript、ビルドなし、`index.html` 1ファイル
- npm やフレームワークは使わない。外部ライブラリは CDN で読み込み、`lib/` にローカルの予備を置く
- 費用はかけない：公開は GitHub Pages、サーバー機能が要るときだけ Firebase の無料枠
- localStorage / IndexedDB のキーは `wcms_` で始める
- 使うのはサークルのメンバー（PCに詳しくない人も含む）。スマホでも使えるようにする
- 個人情報を含むファイルはコミットしない
