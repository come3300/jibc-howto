# githubのやり方について

## github 最初のpush

1,`README.md`が存在しているのかを確認する
//なければ`touch readme.md`等でファイルを作成する
2,`git init`
 `ls -a`
 を実行すると
 .gitというファイルが存在しているはずです
3,`git add .`
// 初期gitリポジトリにある`git add readme.md`でも問題ないです
4,`git commit -m "first commit"`
5,`git branch -M main`
// `git branch`でブランチが作られているか確認してみましょう
6,`git remote add origin git@github.com:jibc-daisuke/1.git`
7,`git push -u origin main`
8,ブラウザが切り替わっていれば完了です。

## github 2回目以降

1,git add . 
//git add ファイル名　git add hello.html
2,git commit -m "コミットメッセージを追加"
3,git push origin ブランチ名


## その他

### git branchについて
### git checkoutについて
### git addについて
### git statusについて

## 小技集

