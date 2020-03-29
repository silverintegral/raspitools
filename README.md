# raspitools

RaspberryPi用ユーティリティ

## telenoty
Telegram連携ツール

### インストール
php-cliをインストールして、telenotyを/usr/bin/にコピーして下さい。

### 設定
環境変数TELENOTY_TOKENとTELENOTY_CHATIDをそれぞれ設定するか、ファイル内の定数TOKENとCHATIDをそれぞれ設定して下さい。

申し訳ありませんが、tokenとidの取得については他をご覧下さい。

### 使い方サンプル
> echo aaa | telenoty

もしくは
> telenoty aaa

でTelegramに文字列を送信します。

IPが変更した時などに投げるようにしておくとメールを受信するよりも簡単に行えます。
