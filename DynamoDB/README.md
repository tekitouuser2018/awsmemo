# DynamoDB

https://aws.amazon.com/jp/dynamodb/

### 特徴
---
https://aws.amazon.com/jp/dynamodb/features/
https://docs.aws.amazon.com/ja_jp/amazondynamodb/latest/developerguide/Introduction.html



### 他のDBとの相違
---

### デメリット
---
1. ベンダーロックイン
2. 結果整合性が取れない
3. 集計に弱い
4. RDBなどとはコンセプトや設計手法も全く異なるため、導入・学習コストが高い
5. 扱うことができるデータ型もRDBと比べると少ない

### ユースケース
---
- streamデータを扱うのに適している
- カラム変更が多く発生する場合

・RTB のユーザープロファイルストアと広告ターゲティング
・ユーザーイベント、クリックストリーム、インプレッションデータストア
・アセット用メタデータストア
・人気アイテムのキャッシュ
・ゲームの状態
・プレイヤーのデータストア
・プレイヤーのセッション履歴データストア
・リーダーボード

https://aws.amazon.com/jp/blogs/database/amazon-dynamodb-ad-tech-use-cases-and-design-patterns/
https://aws.amazon.com/jp/solutions/case-studies/duolingo-case-study-dynamodb/
https://aws.amazon.com/jp/blogs/news/amazon-dynamodb-gaming-use-cases-and-design-patterns/

