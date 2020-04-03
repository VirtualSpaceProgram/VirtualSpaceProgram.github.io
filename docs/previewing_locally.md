# ローカルプレビューする方法
レイアウトやスタイル、文章などを編集した際、ホームページに反映する前にローカル環境で確認する方法について紹介します。

## Jekyllのインストール
1. こちらのページの手順でJekyllをインストールします。
    * [Jekyllインストール](https://jekyllrb-ja.github.io/docs/installation/)

## Clone(ダウンロード)
1. 下記コマンドで必要なデータがダウンロードできます。
    ```
    $ git clone https://github.com/VirtualSpaceProgram/VirtualSpaceProgram.github.io
    ```
## サーバの起動
1. 下記コマンドでサーバが起動します。
    ```
    $ bundle exec jekyll serve
    ```
1. ブラウザで[http://localhost:4000/](http://localhost:4000/)にアクセスするとプレビューできます。