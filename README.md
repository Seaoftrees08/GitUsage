# GitUsage
gitの使い方いっつも忘れるので、自分用のメモ。あ、MIT Lisence律儀に守らなくてもいいよ?

## git init
Create git (only creating)  
gitを作りたいディレクトリ内でこのコマンドを使うことで初期化できます.  

## git add *
Add Files (please replace `*`)  
コミットするファイルを追加します.    

## git commit -m "test"
Commit to Local Repository.  
ローカルリポジトリにコミットします.  
複数人開発時には事前にpullしておくことをおすすめします.  
testの中身はわかりやすい内容にまとめてください(このコミットでは何をしたか.)  

## git remote add origin URL
add URL if you push at the first  
最初にリモートリポジトリにプッシュするまえにどこにプッシュするかの情報を登録します.  
最初の一回だけで大丈夫です.  
例：`$git remote add origin https://github.com/Seaoftrees08/name.git`

## git push origin branch_name
push to Remote Repository  
リモートリポジトリにプッシュします.  

# Team-Development
## git pull
get commit from Remote Repository  
リモートリポジトリから最新のコミット情報を取得します.    

## git branch
ブランチ一覧を表示します.  

## git branch branch_name
新しいブランチを作成します.  

## git checkout branch_name
ブランチを切り替えます.


# First Settings
`$git config --global user.email "you@example.com"`   // set email  
`$git config --global user.name "Your Name"`          // set username 
