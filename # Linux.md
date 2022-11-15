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
- grep
- ping [address] : 通信相手までネットワークが接続できているか確認する
- sudo [command] : スーパーユーザーの権限でコマンドを実行する
- chown : ファイルの所有者やグループを変更する
  - -R : 指定ディレクトリ含め、配下のディレクトリの所有権も再帰的に変更
- yum : パッケージをインストールする
  - install [パッケージ名]
  - update [パッケージ名]
- systemctl : システムサービスなどを操作する
  - start
  - stop
  - restart
  - status
  - enable : 自動起動有効, disable : 自動起動無効

## vi

- vi [ファイルパス]
- i : 挿入モード
- :w : 保存
- :wq : 保存して終了
- :q : 終了。保存されていなければメッセージが表示される
- :q! : 強制終了。ファイルは保存されない
- p : クリップボードの内容をカーソル行の下の行に貼り付ける
- yy : １行コピーしクリップボードへ格納する