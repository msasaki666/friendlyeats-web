# memo

## https://firebase.google.com/codelabs/firestore-web?hl=ja#3

firebase use --addするにはvannila-jsディレクトリに移動する必要がある。[後のページ](https://firebase.google.com/codelabs/firestore-web?hl=ja#5)の記載内容から、このディレクトリであると推測した。

loginしているのに、firebase use --addでエラーが出る。権限がないような感じ。調べると、[cliのバージョンが古い時にログインしていた場合、再ログインが必要](https://chaika.hatenablog.com/entry/2021/02/28/150000)なよう。->成功した

### 実行ログ

```shell
$ firebase use --add 
? Which project do you want to add? friendlyeats-c14c9
? What alias do you want to use for this project? (e.g. staging) default

Created alias default for friendlyeats-c14c9.
Now using alias default (friendlyeats-c14c9)
```
