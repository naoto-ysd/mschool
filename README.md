* データベース設計
## users テーブル
|Column|Type|Options|
|------|----|-------|
|email|string|null: false|
|encrypted_password|string| null: false|
|reset_password_token|string|
|reset_password_sent_at|datetime|
|remember_created_at|datetime|
|nickname|string|null: false|

## teachers テーブル
|Column|Type|Options|
|------|----|-------|
|name|string|null: false|
|instrument|string|null: false|
|address|string|null: false|