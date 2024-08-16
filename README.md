# Cloud
sample cdk for aws

 - 技術スタック
    - Teraform

## 概要
teraformを使用して、各Cloud環境の構築を行う。
Cloud環境におけるサービスについては、コンテナベースにて
build,deployをする。

teraformでの使用言語は、HCLとして記載しているが、
言語としてtypescriptのプラグインを導入した上で運用行う。

 - 作成サービス
    - EC2
    - RDS
    - ECS
    - Lamba
    - CloudWatch

## 環境構築

