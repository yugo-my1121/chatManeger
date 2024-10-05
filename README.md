# 概要
クライアントとサーバでUDP通信を行います。<br>
サーバはクライアントから「name」or「address」の値を受信すると、ランダムで生成した「氏名」or「住所」をクライアントに送信する。

## 前提条件
- Dockerにて、Ubuntu環境で開発したため、使用端末のローカル環境で動作するか確認が取れいていません。
- 「/tmp/chatManeger_client」、「/tmp/chatManeger_server」の２つのファイルを作成する必要があります。

## 使用方法
1. `python3 server.py`でサーバーを起動させる。
2. 新しくターミナルを開いて`python3 client.py`でコマンドインで入力できるようになるので、「name」or「address」を入力する



