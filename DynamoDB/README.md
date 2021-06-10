# DynamoDB

https://aws.amazon.com/jp/dynamodb/

https://pages.awscloud.com/rs/112-TZM-766/images/20190905_%E3%82%A4%E3%83%81%E3%81%8B%E3%82%89%E7%90%86%E8%A7%A3%E3%81%99%E3%82%8B%E3%82%B5%E3%83%BC%E3%83%8F%E3%82%99%E3%83%BC%E3%83%AC%E3%82%B9%E3%82%A2%E3%83%95%E3%82%9A%E3%83%AA%E9%96%8B%E7%99%BA-%E3%82%B5%E3%83%BC%E3%83%8F%E3%82%99%E3%83%BC%E3%83%AC%E3%82%B9%E3%82%A2%E3%83%95%E3%82%9A%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E5%90%91%E3%81%8D%E3%81%AEDB%20%E8%A8%AD%E8%A8%88%E3%83%98%E3%82%99%E3%82%B9%E3%83%88%E3%83%95%E3%82%9A%E3%83%A9%E3%82%AF%E3%83%86%E3%82%A3%E3%82%B9.pdf

### 特徴
---
https://aws.amazon.com/jp/dynamodb/features/
https://docs.aws.amazon.com/ja_jp/amazondynamodb/latest/developerguide/Introduction.html


### デメリット
---
1. ベンダーロックイン
2. 結果整合性が取れない
3. 集計に弱い
4. RDBなどとはコンセプトや設計手法も全く異なるため、導入・学習コストが高い
5. 扱うことができるデータ型もRDBと比べると少ない

### ユースケース
---
1. streamデータを扱うのに適している
2. カラム変更が多く発生する場合
3. 低レイテンシ要求
4. 高アクセス
...など

- RTB のユーザープロファイルストアと広告ターゲティング
- ユーザーイベント、クリックストリーム、インプレッションデータストア
- アセット用メタデータストア
- 人気アイテムのキャッシュ
- ゲームの状態
- プレイヤーのデータストア
- プレイヤーのセッション履歴データストア
- リーダーボード

https://aws.amazon.com/jp/blogs/database/amazon-dynamodb-ad-tech-use-cases-and-design-patterns/

https://aws.amazon.com/jp/solutions/case-studies/duolingo-case-study-dynamodb/

https://aws.amazon.com/jp/blogs/news/amazon-dynamodb-gaming-use-cases-and-design-patterns/

