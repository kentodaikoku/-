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
