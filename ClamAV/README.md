#plist/ClamAV
####`net.clamav.clamd.plist`
ログイン時に`clamd`を自動で起動させます。

####`net.clamav.clamdscan.plist`
スケージュールスキャンの間隔を秒単位で設定します。

####`net.clamav.freshclam.plist` 
ログイン時に`freshclam`をデーモンとし起動させ、パターンファイルの更新を自動でチェックさせます。チェックする回数は**freshclam.conf**で設定してください。

####`net.clamd.wfol.plist`
指定したフォルダ内でファイルの追加/変更があるとスキャンします。`clamd`が起動してないと使えません。

###More Info
詳しくはブログ記事[Mac用アンチウィルスソフトClamXavの使い方と設定のまとめ](http://tukaikta.blog135.fc2.com/blog-entry-205.html)を参照してください。