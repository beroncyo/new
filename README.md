# new
git config --global user.name "アカウント名"
git config --global user.email "メールアドレス"
git hubにリモートリポジトリを作成
ローカルに作業用リポジトリを作成 (作業用ディレクトリを作成し、そこに移動してgit init)
リモートリポジトリの登録
git remote add origin <リモートリポジトリのリンク>
ローカルリポジトリで何かしらのファイルを作成し、リモートリポジトリに反映
(例)
touch test.txt (何かしらのファイル作成)
git add .
git commit -m "initial commit"
git push origin master
