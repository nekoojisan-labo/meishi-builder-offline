# 名刺ビルダー Offline Local Edition

名刺ビルダーは、ブラウザだけで名刺を作成できるローカル利用向けツールです。

このリポジトリの GitHub Pages は、オフライン版 ZIP を配布するためのページです。名刺データをサーバーに預ける設計ではありません。

## 使い方

1. Pages のダウンロードボタンから `meishi-builder-offline.zip` を取得します。
2. ZIP を展開します。
3. `index.html` をブラウザで開きます。
4. 名刺情報を入力し、PDF/PNG/vCard を書き出します。

## データの扱い

- 氏名、住所、画像、下書きデータはサーバーへ送信されません。
- 下書きはユーザーのブラウザ内 IndexedDB に保存されます。
- JSON保存を使うと、ユーザー自身のPCにバックアップできます。
- オフライン版は必要な JavaScript を `vendor/` に同梱しています。

## 配布物

- `downloads/meishi-builder-offline.zip`
