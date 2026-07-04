# git, githubの使い方メモ
## レポジトリの作り方
1. githubのサイト上でレポジトリを作成
1. ターミナルで，アップロードしたいフォルダに移動
1. ```git init```を実行し，リポジトリを初期化
1. `git add .`で全てのファイルをステージングエリアに準備
1. `git commit -m "my first commit"`などで最初のコミットを作成
1. `git branch -M main` で，メインブランチ名を設定　通常main
1. `git remote add origin "url" `でローカルのgitに，githubのリポジトリを登録
1. `git push -u origin main`で，originにmainを送信

## 2回目以降のpush
2回目以降のメインブランチへプッシュは次の通り
1. `git add .`
1. `git commit -m "description of this commit"`
1. `git push`
これでプッシュが可能

## ブランチの切り分け

## プルリクエスト

## git ignore

