# 他の人のリポジトリーの変更依頼を出そう

ここでは他の人のリポジトリーに変更依頼を出すやり方を紹介します。

## forkしよう

ブラウザで https://github.com/fintalk/study-git にアクセスします

![image](images/fork01.png)

forkボタンを押すと、自分のページに study-git リポジトリーが作られます。これがfork（フォーク）です。

![image](images/fork02.png)

この自分のリモート領域にフォークしたリポジトリーをローカルで変更します。

![image](images/fork03.png)

## ローカルで編集できるようにしよう
リモートリポジトリーのコピーしてローカルリポジトリーにするには *クローン* します。
自分の環境の方のリポジトリーで行ってください。

![image](images/fork04.png)

HTTPSのテキストをコピーして、ローカルのフォルダで以下のコマンドを実行します。
新しいリポジトリーを作れるフォルダに移動してから作りましょう。

コピーした `https://` の後ろにユーザー名、パスワードをつけましょう、。

```
cd ..
git clone https://<githubのユーザー名>:<githubのパスワード>@github.com/<user名>/study-git.git
cd study-git
```

これで、study-gitにファイルを追加できる

## やってみよう
workspaceフォルダーの下に新しいファイルを作って自分のリモートリポジトリーにpushしよう

## PR作ってみよう

自分のリモートリポジトリの内容をfork元のリポジトリーに取り込んでもらうための依頼を作成します。
Pull Request を作ります。

![image](images/fork10.png)

![image](images/fork11.png)

![image](images/fork12.png)

## 自分のリポジトリーにPRが着たらレビューしよう

自分のリポジトリーにPull Requestが来たらレビューして取り込みましょう。

![image](images/fork20.png)

![image](images/fork21.png)

PR内容が良ければ Approve を選択します。
その後、mergeします。
