# Subversion のリポジトリを Git のリポジトリに変換する

## trunk, branches, tags が正しく運用されているリポジトリの場合
* GitHubDesktop の Git Shell を利用する

### Git Shell を起動する
* スタートメニューの `GitHub, Inc` => `Git Shell` から Git Shell を起動


### リポジトリを持ってきたいフォルダに移動する


### clone
```
git svn clone [Subversion Repository] -s
```

* Subversion のリポジトリを一からチェックアウトして Git にコミットするを繰り返すので、結構時間がかかる。
