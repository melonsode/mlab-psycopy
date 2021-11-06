# 補講 2021.11.6 土

with t and o

## gitのインストール
 - mac はデフォルトのものを使用
 - 昨日のインストールよりバージョン古い
 - user.name と user.email の設定で戸惑い

## githubのアカウント作成
 - アカウント作成 , melonsodeのリポジトリを探してもらう
 - mlab-psyachopyのページからcloneしてもらう
 - 最初は簡単なhttps プロトコル
 - git pushをするにはsshプロトコル必要

## ssh-keygen
 - 公開鍵が作成されているか確認
 - ないので、ssh-keygenで作成
 - pubをgithubのページに登録
 - https://docs.github.com/ja/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account
 - Settings->SSH and GPG keys
 - .git/configの書き換え urlをSSHに
 - https://tks2.co.jp/2021/01/18/github-ssh/


## git push, git pull ができることを確認
 - git push, git pullができ、お互いのコードをシェアできた


## その他
 - テキストエディタを手に入れる(sublime, Atom, VSCode)
 - PsychoPyのコードは簡単に共有できるのか？
 - CUIエディタの使い方難しい nano, vi

## vi
 - iでインサートモード
 - 入力が終わったら esc
 - :w で保存、 :q で終了、 :wq

## 覚えておきたいコマンド
 - ch : change directory
 - ls : list, ls -l, ls -a
 - touch, rm, mv, cp
 - mkdir : make directory
 - デフォルトの場所を表す特殊記号　~（チルダ） 

## マークダウン記法
 - https://gist.github.com/mignonstyle/083c9e1651d7734f84c99b8cf49d57fa 

## gitの基本的なコマンド
 - git clone <リポジトリURL>
 - git add <ファイル名>
 - git commit -m "comment"
 - git push
 - git pull = git fetch + git merge






