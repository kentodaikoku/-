# Laravel Artisan 

## インストール
```
composer create-project laravel/laravel --prefer-dist { } ("9.x")
```

## overall

- artisan --version
- artisan route:list

## make

- make:controller []
  - --resource
- make:model []
  - --m (マイグレーションファイル同時作成)
- make:migration create_[~s]_table
  - --create=[~s] (テーブル作成)
- make:request []
- make:seeder []
- make:middleware


## migration

- migrate
- migrate:status
- migrate:fresh --seed
- migrate:rollback //ひとつ前のマイグレーション操作に戻す

## clear

- cache:clear
- config:clear
- route:clear
- view:clear
