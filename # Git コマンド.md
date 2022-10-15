# Git コマンド

## 設定コマンド
- git config --global user.name []
- git config --global user.email []
- git config --global --list
- git remote set-url origin https://<ユーザ名>@github.com/<ユーザ名>/<リポジトリ名>.git

## 操作コマンド
- git init 
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
  - git branch -M [main]
  - git branch -d <bra_name>
- git checkout <bra_name>
  - git checkout -b <bra_name>
- git merge <bra_name>
  - --continue
- git merge-base <branch1> <brnach2>
  - 分岐したコミットの確認
- git log
  - git log --graph
- git clone 
  - git clone --depth=1
- git rebase
  - ブランチの分岐元を変更
  - コミット履歴の修正（-iオプション）☆


## git fllow

- main / develop
- feature
- release(staging)
- hotfix
