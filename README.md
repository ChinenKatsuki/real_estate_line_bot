# 賃貸ヒアリングボットくん

[賃貸ヒアリングボットくん](https://user-images.githubusercontent.com/67732612/118601028-19a44a80-b7f5-11eb-9558-608b818b59f0.JPG)<br>
[友達追加はこちら](https://line.me/R/ti/p/%40155jsgma)

# コンセプト

24時間365日いつでも登録可能！<br>
質問に答えるだけで簡単にユーザーの要望をヒアリング！

# ターゲット層

* 賃貸物件を取り扱っている不動産会社

# 機能

1. 2つの質問機能
  * 質問の回答は全てデータベースに保存
  * リッチメニュー機能を使い文字を入力せずに質問を開始することができます
  * 「個人情報入力」と入力すると個人情報に関する質問を開始することができます
1. トーク機能
  * talk apiを使い文字列を入力すると会話することができます
1. 通知機能
  * ラインボットに登録時、slackに通知。グーグルカレンダーにも登録
  * 賃貸に関する質問の回答を全て終わるとslackに通知
  * 個人情報に関する質問の回答を全て終えるとslackに通知
1. バッチ処理機能
  * 毎日24時にその日のラインボット登録人数をslackに通知

# デモ動画
[賃貸に関する質問](https://user-images.githubusercontent.com/67732612/118600848-e5308e80-b7f4-11eb-9662-1f8cbeba3ef6.gif)
[個人情報に関する質問](https://user-images.githubusercontent.com/67732612/118602043-7d2e7800-b7f5-11eb-9c39-998509001f44.gif)

# 開発環境

* サーバー：Linux(CentOS)
* データベース：MySQL 5.6.44
* エディター：Vim
* 言語：PHP 7.1.29

# Note

# Author

* Katsuki
