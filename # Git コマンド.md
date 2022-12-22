# Git コマンド

## 設定コマンド

- git config --global user.name []
- git config --global user.email []
- git config --global --list
- git remote set-url origin https://<ユーザ名>@github.com/<ユーザ名>/<リポジトリ名>.git

## githubから新規レポジトリ作成後の初期設定

### 1. ローカルレポジトリ未作成
```
1. echo "# git_practce" >> README.md 
2. git init
3. git add README.md
4. git commit -m "first commit"
5. git branch -M main
6. git remote add origin [remote_repo_url]
7. git push -u origin main
```


### 2. ローカルレポジトリ作成済み
```
1. git remote add origin [remote_repo_url]
2. git branch -M main
3. git push -u origin main
```


## 操作コマンド

- git add
  - git add .
  - git add -A

- git commit -m ""

- git diff
  - git diff <コミットハッシュ> <branch_name> <file_name>
    - コミット時の修正内容の確認

- git status

- git push origin [main]
- git pull origin [main]

- git branch
  - -M [main]
  - -d <bra_name>
  - --sort=authordate

- git checkout <bra_name>
  - git checkout -b <bra_name>

- git swtich <bra_name>
  - -c <bra_name>

- git merge <bra_name>
  - --continue
  - --no-ff : no fast-forward

- git merge-base <branch1> <brnach2>
  - 分岐したコミットの確認

- git log
  - git log --graph

- git clone 
  - git clone --depth=1

- git rebase
  - ブランチの分岐元を変更
  - コミット履歴の修正（-iオプション）☆

- git remote -v
  - リモートレポジトリのURLを確認

# git fllow

- main / develop
- feature
- release(staging)
- hotfix

## github fllow

- main(master)
- feature