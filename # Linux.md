# Linux

## バージョン確認系

- mysql --verison
- centoOS
  - cat /etc/redhat-release
- apache
  - httpd -v

## コマンド

- Select-String
  - Select-String 検索対象文字列 検索対象ファイル -Encoding default
- cat
- less
- sudo : スーパーユーザーの権限でコマンドを実行する
- yum : パッケージをインストールする
  - yum install [パッケージ名]
  - yum update [パッケージ名]
- 

## vi

- vi [ファイルパス]
- i : 挿入モード
- :w : 保存
- :wq : 保存して終了
- :q : 終了。保存されていなければメッセージが表示される
- :q! : 強制終了。ファイルは保存されない
- p : クリップボードの内容をカーソル行の下の行に貼り付ける
- yy : １行コピーしクリップボードへ格納する