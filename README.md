# 概要
crontabの練習用リポジトリ

# crontabで使用したコマンド

``` sh
* * * * * $HOME/app/shell/test.sh >> $HOME/app/shell/log.txt
```


# その他
ファイルの権限の問題で動かない可能性がある。
chmodコマンドを適用すること

