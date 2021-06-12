# AWS memo

## 基本構成

https://dev.classmethod.jp/articles/creation_vpc_ec2_for_beginner_1/

https://docs.aws.amazon.com/ja_jp/vpc/latest/userguide/VPC_Subnets.html

1. リージョン選択
2. VPC作成。RFC1918基準でIPv4 CIDR ブロック設定。
3. VPCにサブネットを作成する。Public, Private。
4. インターネットゲートウェイを作成しVPCにアタッチする。
5. ルートテーブルを作成する。
6. ルートテーブルにインターネットゲートウェイへのルートを登録する。
7. ルートテーブルにサブネットを関連づける。
