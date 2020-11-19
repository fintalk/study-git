# GitHubを利用しよう

## リポジトリを作る

リモート側の作業領域（リポジトリー）をGitHub側に作ります。

![image](images/github_02.png)

![image](images/github_03.png)

*Repository name* に好きなリポジトリー名をつけてください。リポジトリー名は後で変更できるのでそんなに悩まなくていいです。
Publicを選ぶと全世界の人に公開されるリポジトリーになります。Privateを選ぶとあなたが許可した人にしか公開されないリポジトリーになります。
選択が終わったら、*Create repository* ボタンをクリックします。

![image](images/github_05.png)

リポジトリーが作成されたら、ローカルの作業領域（ローカルリポジトリー）と連動するやり方が表示されます。

![image](images/github_06.png)

書いてある通りにやります。パスワードを利用しているので、GitHubのユーザー名とパスワードを間に挟みます。

```
git branch -M main  # ローカルのブランチ名がmasterの人はmainに改名します。元のブランチ名がmainの人は不要です
git remote add origin https://<githubのユーザー名>:<githubのパスワード>@github.com/<user名>/<リポジトリ名>.git
git push -u origin main
```

![image](images/github_01.png)

![image](images/github_04.png)

## やってみよう

ローカルでファイルを追加し、GitHubのリポジトリにpushしましょう。
2回目からは `git push` だけでpushできます。
