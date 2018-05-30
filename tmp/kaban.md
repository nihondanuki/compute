# InChaos
validate_each
責務を分けていく デコレータ
フォームオブジェクトにファクトリーを使うな
requireするとない場合にエラーになる
nilガード  
ストロングパラメーター
article modelを使っている
render views
like検索の時sanitize_sql_likeを入れる


# be_predicate
predicateマッチャはbe_で始まるもの

例外が二つあり
- be_truthy
- be_falsey

マッチャーは指摘されたら直すのでいいかもしれない
意図したテストになっていれば問題ない
マッチャを使うことによって英語としてちゃんとしたものになるのでossなら気をつけるべき

実際に書いて見て気づいたこと
マッチャーの判断タイミング
リファクタリングのタイミング

# 統合テストのdescribeはclass

# チップス
ideは知識が必要 vimで書かなきゃ

# デコレーターパターン
```ruby
include ActiveModel::Model
```
invalidはactivemodel::modelについている

モデルは３つあり
- アクティブレコード
- アクティブモデルモデルを継承するクラス
- クラス 普通のclass

# MVC
viewの責務 オブジェクトの読み込み

# acitverecord
find クエリ
アトリビュート　がデータ
アクティブレコードはモックを作るのが困難
apiが複雑　アクティブレコード
テーブルと関連づくばあいはアクティブレコード
