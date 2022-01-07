## プロジェクト作成
```composer create-project "laravel/laravel=6.0.*" --prefer-dist csvexport```

## 動作確認
```php artisan serve --port=8080```

## 開発時ストレージ
database.sqliteをdatabase直下に配置  
.envファイルに```DB_CONNECTION=sqlite```を記載してDB関連の行をコメントアウト

## テーブルをDBに作成
```php artisan migrate```

## テーブルにデモデータを投入する
```php artisan db:seed```
