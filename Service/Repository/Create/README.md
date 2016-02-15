レポジトリの作成
=============

## ページを開く
* [レポジトリを作成したいグループ](https://github.com/MiharuCommunications) を開く
* [New Repository](https://github.com/organizations/MiharuCommunications/repositories/new) をクリック

![New Repository](./new-repository.jpg)


## レポジトリの情報を入力
### Owner (コンボボックス)
* レポジトリの所有者です
* MiharuCommunications にしておいてください


### Repository name (テキストボックス)
* レポジトリの名前です。 (URL 等に使用されるものです)
* 半角英数字ベースです。
* グループ内で重複がなく、分かりやすいものでお願いします。


### Description (optional) (テキストボックス)
* レポジトリの説明です
* 日本語も使えます
* 無くてもいいです



### Public or Private
* レポジトリを公開するかどうかです
* `Public` にすると、誰でも見ることが出来ます。 (全世界公開です)
* `Private` にすると、グループに入っている人からしか見れなくなります。
* 社内で公開すると決まってない場合は、`Private` にしてください。


### Initialize this repository with a README
* レポジトリに `README.md` ファイルだけを入れた状態で初期化するかどうかです。
* 既存のレポジトリを引っ越しさせる場合でなければ、チェックを入れておいたほうがいいです
    * チェックを入れない場合、ブランチ数 0 で生成され、初期化を別途しないといけないです。
    * 既に、レポジトリが別の場所に存在する場合、チェックを外せば引っ越し処理が出来ます


### Add .gitignore
* `Git` の管理で無視するファイルのパターンを記録したファイルです。
* よくあるパターンを自動生成してくれます。 (Visual Studio, C 等)


### Add a license
* よくあるライセンスのライセンス条文が入ったファイルを自動生成してくれます
* 社内の場合は `None` で問題無いです。



## ローカルにクローン
### [GitHub Desktop の場合](./CloneGitHubDesktop.md)

### [SourceTree の場合](./CloneSourceTree.md)
