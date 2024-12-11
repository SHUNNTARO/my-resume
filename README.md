# 概要
自身のポートフォリオサイトを作成しました。

# サイトURL
https://kakkeeess-website.com
（料金の関係で現在AWSを解約したためアクセスできません）

# 目的
* 本番環境のウェブサーバ環境の構築。
* AWS の EC2 を使用して、クラウドのエコシステムに足を踏み入る。
* SSH シェルと Git ソース管理ツールを使ってサーバの管理。
* ファイルを配信する静的ウェブサーバを作成。
* NGINX を使用し、さまざまなシナリオで動作するように設定する。
* DNS について学び、独自のドメインを設定する。
* TLS による安全な暗号化について学び、独自の証明書を作成して HTTP セキュアを設定する。

# 使用技術
<p style="display: inline">　
  <img src="https://img.shields.io/badge/-Ubuntu-E95420.svg?logo=ubuntu&style=social">
  <img src="https://img.shields.io/badge/-Nginx-269539.svg?logo=nginx&style=social">
  <img src="https://img.shields.io/badge/-Html5-E34F26.svg?logo=html5&style=social">
  <img src="https://img.shields.io/badge/-Css3-1572B6.svg?logo=css3&style=social">
  
</p>

# 概要

### コマンド一覧

| コマンド                | 実行する処理                                                            | 
| ------------------- | ----------------------------------------------------------------------- | 
| sudo mkdir -p /var/www/project/public        | ウェブサイトは /var/www/{website} の下に置くのが一般的、/var/www/{website} の下に新しいフォルダを作り、適切なアクセス権限を設定 | 
| sudo ln -s PATH /var/www/project/public             | フォルダの間にシンボリックリンクを作成                                                         | 


