# image-gallery-tutorial

このチュートリアルは[この動画教材](https://youtu.be/k1yULKWfO-s)の丸パクリからスタートしています。
この学習をとおして学んだことのポイントや、カスタマイズしたことの軌跡をこのリポジトリに残して、自分も含め少しでも読者の参考になれば幸いです。  
ではやってみましょう！

【動画教材の演習でお世話になったサイト】

 1. [lightbox2公式サイト](https://lokeshdhakar.com/projects/lightbox2/#getting-started)
 1. CDN検索サイト[cdnjs](https://cdnjs.com/libraries)
 1. 教材用画像の[提供元リポジトリ](https://github.com/Shin-sibainu/image-gallery-with-lightbox) zipでダウンロード

## Github PagesのActionsを設定してサイト公開する

### 1. ローカルのプロジェクトからgithubにアップロード

- ブラウザからGithubにログインし、新規リポジトリ<i>repo-name</i>を作成し、下記コマンドをローカルのターミナルから叩いてチュートリアルの成果物をgithubにアップロード

```bash
cd project-path        #プロジェクトルートに移動
git init               #必要ならgitを初期化する
git add .　　　　        #ステージング
git commit -m "initial commit"
git branch -M main      #既定のブランチ名masterをmainに変更する
git remote add origin https://github.com/user/repo-name.git #リモートリポジトリを設定
git push -u origin main #Githubにアップロード
```

【お世話になったサイト】
[git remote addを取り消す方法](https://qiita.com/ngtkk/items/05097d127db6a415a7d8)

- GitHub Pagesの設定
