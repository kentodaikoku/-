# Git コマンド

- git remote set-url origin https://<ユーザ名>@github.com/<ユーザ名>/<リポジトリ名>.git

- git merge-base <branch1> <brnach2>
  - 分岐したコミットの確認

- git diff <コミットハッシュ> <branch_name> <file_name>
  - コミット時の修正内容の確認

- git merge
  - --continue

- git rebase
  - ブランチの分岐元を変更
  - コミット履歴の修正（-iオプション）☆

- --continueオプション


## git fllow

- main / develop
- feature
- release(staging)
- hotfix