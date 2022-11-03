# Laravel Artisan 

## インストール
```
composer create-project laravel/laravel --prefer-dist { } ("9.x")
```

## overall

- artisan --version
- artisan route:list

## make

- artisan make:controller []
  - --resource
- artisan make:model []
  - --migration (マイグレーションファイル同時作成)
- artisan make:migration create_[~s]_table
  - --create=[~s] (テーブル作成)
- artisan make:request []
- artisan make:seeder []
- artisan make:middleware


## migration

- artisan migrate
- artisan migrate:status
- artisan migrate:rollback //ひとつ前のマイグレーション操作に戻す

## clear

- artisan cache:clear
- artisan config:clear
- artisan route:clear
- artisan view:clear
