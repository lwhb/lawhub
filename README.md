# lawhub
日本の法令データをGitHubで管理することを目的としたレポジトリです。  
本レポジトリは自然言語処理を用いて機械的に更新されており、内容の正当性は保証しません。

現在、以下の機能がサポートされています。
* [e-Gov](https://elaws.e-gov.go.jp/download/lawdownload.html)の法令データにあわせてmasterブランチを更新する ([releases](https://github.com/lwhb/lawhub/releases))
* [衆議院](http://www.shugiin.go.jp/internet/itdb_gian.nsf/html/gian/menu.htm)の議案データにあわせてfeatureブランチを作成し、pull requestを作成する ([pulls](https://github.com/lwhb/lawhub/pulls))

次の機能は含みません。
* 作成したpull requestをマージする
* 議案提出者に応じてauthorを変更する


![diagram](diagram.png)
