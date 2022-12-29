[AWSコンテナ設計・構築［本格］入門](https://www.amazon.co.jp/AWS%E3%82%B3%E3%83%B3%E3%83%86%E3%83%8A%E8%A8%AD%E8%A8%88%E3%83%BB%E6%A7%8B%E7%AF%89%EF%BC%BB%E6%9C%AC%E6%A0%BC%EF%BC%BD%E5%85%A5%E9%96%80-%E6%96%B0%E4%BA%95-%E9%9B%85%E4%B9%9F-ebook/dp/B09DKZC1ZH/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=&sr=)

# sbcntr-resources

書籍用の各種リソースのダウンロードリポジトリです。

## リポジトリの構成

```bash
❯ tree . -d 1
.
├── cicd
├── cloudformations
├── cloud9
├── fargate-bastion
├── firelens
├── iam
└── scan
```

それぞれのディレクトリと本書の関連付けは次の通りです。

| ディレクトリ          | 本書の対象箇所                                                    | 内容                                               |
|-----------------|------------------------------------------------------------|--------------------------------------------------|
| cicd            | 5-2 運用設計:Codeシリーズを使った CI/CD                                | CI/CD設計で利用するビルド定義やタスク定義などを格納                     |
| cloudformations | 4-2 ネットワークの構築, 4-4 コンテナレジストリの構築, 4-5 オーケストレータの構築, 付録1 | ハンズオンや付録で利用するCloudFormationを格納                      |
| cloud9          | 4-4 コンテナレジストリの構築   | resize.shを格納 |
| fargate-bastion | 5-7 運用設計:FargateによるBastion(踏み台ホスト)の構築                      | Fargate Bastionで利用するBastionコンテナの設定を格納            |
| firelens        | 5-6 運用設計 &セキュリティ設計:ログ収集基盤の構築                               | ログ収集基盤のFireLensコンテナに設定するログ設定を格納                  |
| iam             | 4章、5章全般                                                    | 4章や5章の各所で利用するIAMポリシーのJSONファイルを格納                 |
| scan            | 5-8 セキュリティ設計:  Trivy/Dockleによるセキュリティチェック                   | DevSecOpsを実現するためのCodeBuildのビルド定義を格納              |

本書でPDFからコードをコピー＆ペーストしたり、写経するのが難しい場合がありますので、是非ご活用ください。
