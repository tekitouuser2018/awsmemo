# AWS memo

## 基本構成

https://dev.classmethod.jp/articles/creation_vpc_ec2_for_beginner_1/

https://docs.aws.amazon.com/ja_jp/vpc/latest/userguide/VPC_Subnets.html

1. リージョン選択
2. VPC作成。RFC1918基準でIPv4 CIDR ブロック設定。
3. VPCにサブネットを作成する。
4. インターネットゲートウェイを作成しVPCにアタッチする。サブネットに関連付けられているルートテーブルにインターネットゲートウェイへのルートがある場合、そのサブネットは「パブリックサブネット」と呼ばれます。インターネットゲートウェイへのルートを持たないルートテーブルに関連付けられているサブネットは、「プライベートサブネット」と呼ばれます。
5. ルートテーブルを作成する。
6. ルートテーブルにインターネットゲートウェイへのルートを登録する。
7. ルートテーブルにサブネットを関連づける。


## 料金

https://blog.serverworks.co.jp/2020/08/05/193707

https://dev.classmethod.jp/articles/reduce-unnecessary-costs-for-nat-gateway/
