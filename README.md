# koshiki_local

H1 「甑島方言アクセントデータベース」の検索システム (The search system for "Accent Database of Koshikijima Japanese")


- ローカルマシンで検索システムを起動する

`
$ docker run -d --name koshiki_local -p 80:80 -v {YOUR DATA PATH}/html/:/var/www/html ykinjo/koshiki_local
`

ブラウザで "http://localhost:80" にアクセスする。

- 検索システムを停止する

`
$ docker stop koshiki_local 
`
