# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリとは、ネット上に配置して複数人で共有するためのリポジトリです。
- ローカルリポジトリとは、開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリです。


## プッシュとマージの違いは何でしょうか？
- プッシュはローカルリポジトリのデータとリモートリポジトリのデータを同期することです。
- マージは同じリポジトリの中にあるブランチのデータを同期することです。


## コミットとプッシュの違い
- コミットはリポジトリの中にあるデータを保存することです。
- プッシュはコミットしたデータを他のリポジトリに同期することです。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 簡潔にわかりやすく書くことが最適です。
→featやfixなどのprefixを使うと、変更したところがわかりやすいです。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルだと自身でマージすることができます。
- プルリクエストだとレビューアが確認をしてマージするので、バグが見つかりやすくなります。チームでの開発ではこちらがよく使われます。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 上長やソースコードを書いた人（チーム）と相談しながら、作業を進めていきます。
→チームが同じ意図をもって、作業をしなければ要件に一致するものが作れないからです。

