# GitHubを利用しよう

## リポジトリを作る

![image](images/github_02.png)

![image](images/github_03.png)

![image](images/github_05.png)

![image](images/github_06.png)

残りを書いてある通りにやります。パスワードを利用しているので、GitHubのユーザー名とパスワードを間に挟みます。

```
git branch -M main  # 元のブランチ名がmainの人は不要です
git remote add origin https://<githubのユーザー名>/<githubのパスワード>@github.com/<user名>/<リポジトリ名>.git
git push -u origin main
```

![image](images/github_01.png)

![image](images/github_04.png)

## やってみよう

ローカルでファイルを追加し、GitHubのリポジトリにpushしましょう。
2回目からは `git push` だけでpushできます。
