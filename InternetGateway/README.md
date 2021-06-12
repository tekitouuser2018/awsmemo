# Internet Gateway

https://docs.aws.amazon.com/ja_jp/vpc/latest/userguide/VPC_Internet_Gateway.html

https://milestone-of-se.nesuke.com/sv-advanced/aws/internet-nat-gateway/

https://blog.serverworks.co.jp/aws-gateways-1

インターネットゲートウェイは、VPC とインターネットとの間の通信を可能にする VPC コンポーネントであり、冗長性と高い可用性を備えており、水平スケーリングが可能です。

インターネットゲートウェイは 2 つの目的を果たします。
1 つは、インターネットでルーティング可能なトラフィックの送信先を VPC のルートテーブルに追加することです。
もう 1 つは、パブリック IPv4 アドレスが割り当てられているインスタンスに対してネットワークアドレス変換 (NAT) を行うことです。
