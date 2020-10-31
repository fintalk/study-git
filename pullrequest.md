# 他の人のリポジトリーの変更依頼を出そう

## forkしよう

ブラウザで https://github.com/fintalk/study-git にアクセスします

![image](images/fork01.png)
![image](images/fork02.png)
![image](images/fork03.png)

## ローカルで編集できるようにしよう
自分の環境の方のリポジトリーを *クローン* する

![image](images/fork04.png)

コピーして、ローカルのフォルダで実行。
新しいリポジトリーを作れるフォルダに移動してから作ろう

`https://` の後ろにユーザー名、パスワードをつける

```
cd ..
git clone https://<githubのユーザー名>:<githubのパスワード>@github.com/<user名>/study-git.git
cd study-git
```

これで、study-gitにファイルを追加できる

## やってみよう
workspaceフォルダーの下に新しいファイルを作ってpushしよう

## PR作ってみよう

PRを作ってみましょう

![image](images/fork10.png)

![image](images/fork11.png)

![image](images/fork12.png)

## 自分のリポジトリーにPRが着たらレビューしよう

![image](images/fork20.png)

![image](images/fork21.png)

