# Aizu-Graduation-Thesis-Template

## 概要
某大学生のために作った、Texのテンプレートです。wordのレイアウトなどで苦しんでいる方は、Texのほうがもしかするといいかもしれません。

## 使い方
1. zip Downloadでダウンロードし、zipファイルを展開する
2. 展開したフォルダの中に入り、ターミナルで以下のコマンドを実行（学籍番号には自分の番号を入力）
```shell
scp 学籍番号@sshgate.u-aizu.ac.jp:/usr/local/texlive-2016/texmf-local/tex/aizu/U-AizuGT.cls .
```
後は、platexでビルドするなり、IDEを使うなりしてください。個人的におすすめなのは、Tex Studioです。

## 参考
bibliographystyleは、ieicetrを採用しました。こちらからダウンロード致しました。
[http://www.ieice.org/ftp/](http://www.ieice.org/ftp/)
