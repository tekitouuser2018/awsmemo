# ElasticIP

https://docs.aws.amazon.com/ja_jp/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html

- AWSでは通常インスタンスのIPv4パブリックIPは自動割り当てとなるが、ElasticIPを割り当てすることによって静的なIPv4パブリックIPを設定できる。
- 現在、IPv6 に対する Elastic IP アドレスはサポートされていません。

### 料金

https://aws.amazon.com/jp/premiumsupport/knowledge-center/elastic-ip-charges/

https://aws.amazon.com/jp/ec2/pricing/on-demand/#Elastic_IP_Addresses

- 例えば起動停止したEC2インスタンスにElasticIPを割り当てている場合料金が発生するため、起動停止中のインスタンスからはElasticIPの割り当てを解除する必要がある。

