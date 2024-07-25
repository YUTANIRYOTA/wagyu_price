## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリ
 ネット上に配置して複数人で共有するためのリポジトリ。(個人開発用にも使えます)
- ローカルリポジトリ
 開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ。


## プッシュとマージの違いは何でしょうか？
- プッシュ　リモートリポジトリに変更内容を反映すること  
- マージ　別のブランチの作業内容(変更履歴)をブランチに取り込むこと


## コミットとプッシュの違い

- コミット　ローカルリポジトリに変更内容を保存すること  
- プッシュ　リモートリポジトリに変更内容を反映すること

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

- **どんな編集を行ったか一目で変更内容がわかるように書く**

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- プルリクエストを作成し、コードレビューをしてからマージするという手順を踏むことで,  
**事前にバグを発見する事ができる**


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 先にマージされた変更内容を取り込む  
- 後にマージしようとしている変更内容を取り込む  
- どちらの変更内容も取り込む  
いずれかの方法で変更を取り込む