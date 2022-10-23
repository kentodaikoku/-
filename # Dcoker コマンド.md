# Dcoker コマンド

- docker system prune (-a)
    - dockerの不要なゴミ掃除
    - Reset to factory default で再起動しとく
- docker image
  - ls (-a)
  - bulid 
    - (-t)：タグ名
- docker container
  - ls (-a)
  - run [コンテナタグ名]
    - (-it) :インタラクティブモード
    - (-p) ：ポート番号設定
    - (--name) ：
    - (-v)：ボリューム設定（ローカルパスと同期）
  - logs
  - exec
  - rm [コンテナ名]
- dokcer ps (-a)

## docker-compose コマンド
- bulid
- up -d
- down
- ps
- logs
- run [サービス] [コマンド]
- exec [サービス] [コマンド]

## sail コマンド
- ディレクトリ作成or移動
- % curl -s "https://laravel.build/example-app" | bash
- 作成プロジェクト配下に移動
- % ./vendor/bin/sail up
  - sail up (-d)
- http://localhost/ にて起動できてるかの確認
- sail ~ にコマンド変更
  - vi ~/.zshrc
  - alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail' 
  - % source ~/.zshrc
  - 以降はsail ~ でコマンド実行
- sail down
- sail stop ：コンテナがバックグラウンド上で実行されているときの停止法