# 賃貸ヒアリングbot

![賃貸ヒアリング](https://user-images.githubusercontent.com/67732612/119969276-b20aae00-bff1-11eb-8979-4277d23d2283.JPG)

[友達追加はこちら](https://line.me/R/ti/p/%40155jsgma)

# コンセプト

24時間365日いつでも登録可能！<br>
質問に答えるだけで簡単にユーザーの要望をヒアリング！

# ターゲット層

* 賃貸物件を取り扱っている不動産会社

# 機能

1. 2つの質問機能

    - 質問の回答は全てデータベースに保存
    - リッチメニュー機能を使い文字を入力せずに質問を開始可能
    - 「個人情報入力」と入力すると個人情報に関する質問を開始可能

1. トーク機能

    - **talk API**を使い文字列を入力すると会話が可能

1. 通知機能

    - ラインボットに登録した後、slackに通知
    - 賃貸に関する質問の回答を全て終えるとslackに通知
    - 個人情報に関する質問の回答を全て終えるとslackに通知
    - 面談を予約した後、グーグルカレンダーに登録し、slackに通知

1. バッチ処理機能

    - 毎日24時にその日のラインボット登録人数をslackに通知

# デモ動画
| 賃貸に関する質問 | 個人情報に関する質問 |zoom機能 | トーク機能 |
|----------------- | -------------------- | ------- | ---------- |
| ![賃貸に関する質問](https://user-images.githubusercontent.com/67732612/119961367-50464600-bfe9-11eb-98fa-b795b0474177.gif) | ![個人情報に関する質問](https://user-images.githubusercontent.com/67732612/119958108-0f006700-bfe6-11eb-85b0-0d777453a0b6.gif) | ![zoom面談を予約](https://user-images.githubusercontent.com/67732612/119958145-1889cf00-bfe6-11eb-8ae2-3a6c5ba93052.gif) | ![トーク機能](https://user-images.githubusercontent.com/67732612/119958235-322b1680-bfe6-11eb-974f-4dfcf33fbf6c.gif) |

# 表示画面

* **グーグルマップAPI**を使いお客様の住みたい地域を表示

![表示画面](https://user-images.githubusercontent.com/67732612/119958200-263f5480-bfe6-11eb-88e6-a217bf565c3a.png)


# 開発環境

* サーバー：Linux(CentOS)/7.6.1810
* ウェブサーバー：Apache/2.4.6
* データベース：MySQL/5.6.44
* エディター：Vim
* 言語：PHP/7.1.29, Laravel5.5

# Author

* Katsuki
