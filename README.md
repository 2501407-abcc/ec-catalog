# 商品カタログ ECサイト

PHP + MySQLで作った、商品の一覧・検索・詳細・管理者用CRUD・画像アップロード機能を持つWebアプリ。

## 使用技術
- PHP 8
- MySQL
- XAMPP（ローカル開発環境）

## セットアップ手順
1. `schema.sql` をphpMyAdminで実行し、データベースを作成する
2. `seed_data.sql` を実行し、サンプルデータを投入する
3. `.env.example` を `.env` にコピーし、DB接続情報を記入する
4. XAMPPのドキュメントルートを `public_html/` に向ける
5. `http://localhost/items.php` にアクセスする