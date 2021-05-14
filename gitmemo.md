# git memo＜ローカル＞

gitで管理するフォルダで作業を行う

## gitに登録
~~~
git init
~~~
## gitで管理するファイルを登録
~~~
git add --all
~~~
~~~
git add -A
~~~

## gitの状態をみる
~~~
git status
~~~

## 変更を反映
~~~
git commit
git commit -a
git commit -m 'comment****'
~~~

## 過去のログを見る
~~~
git log
~~~

# git memo＜リモート関連＞
## アップロードする
~~~
git remote add origin git@github.com:ibtosmlin/atctool.git
git push --set-upstream origin master
~~~
## ダウンロードする
~~~
git pull git@github.com:ibtosmlin/atctool.git
~~~
