# 職務経歴書

## 基本情報

|項目|内容|
|----|----|
|氏名|鈴木 浩平|
|生年月日|1979/06/28|
|居住地|福岡県福岡市|
|職業|フリーランス<br>ソフトウェアエンジニア|
|稼働状況|余裕あり(2020/10時点)|
|SNS|[Facebook](https://www.facebook.com/kohei.suzuking/)|

## スキル

### 言語

- PHP 4~7
- Java 1.3, 1.4, 6, 8, 11
- JavaScript(Node.js ~12.x)
- Python
- Go
- C, C++, C#
- TypeScript
- などなど

### フレームワーク

- Spring Boot 1.5.x~2.2.x (Java)
- CodeIgniter 2.x (PHP)
- Laravel 5.8 (PHP)
- Yii 2.0.x (PHP)
- Vue.js(Nuxt.js 2.4.x) (JavaScript)
- React 16.x (JavaScript)
- Angular 2.0~6.0 (JavaScript)
- jQuery (JavaScript)
- などなど

### RDBMS + NoSQL

- MySQL 4.1~8.0(+Amazon Aurora)
- Amazon DynamoDB
- Redis
- memcached
- などなど

### その他

- クラウドサービス
  - AWS
    - EC2, Lambda
    - RDS, DynamoDB, ElastiCache
    - S3, CloudFront, API Gateway
    - SES, SNS, SQS, CloudWatch
    - Chatbot, CloudFormation(CDK)
    - などなど
- SaaS
  - Auth0
  - Stripe
  - SendGrid
  - Twilio
  - New Relic
- 仮想化
  - Docker
  - Vagrant(+Chef)
- バージョン管理ツール
  - Git
  - Subversion
- CI/CD
  - GitHub Actions
  - GitLab Runner
  - CircleCI
  - AWS CodePipeline(+CodeBuild, CodeDeploy)
- プロジェクト管理ツール
  - Backlog
  - Redmine
- チャットツール
  - Slack
  - Chatwork
- ビデオチャットツール
  - Google Meet
  - Zoom
  - Microsoft Teams
  - Discord

## 強み

- 数百万人以上の大規模Webサービスの運用・開発経験
- ガラケー(低スペックサーバ)時代に培った技術と経験
- あらゆる環境、開発手法やプロセスの経験
- コーディングのスピードと正確性

## やったことはないが興味があるもの

- 実務レベルでの一からのフロントエンド開発(趣味や個人サイトではあるが実務では基盤構築からはほぼなし)
- Amazon ECSやKubernetesを使った本番環境でのコンテナ運用(経験はゼロではないがもう少し本格的に経験したい)

## 資格

#### [デジタルバッジ(Acclaim)](https://www.youracclaim.com/users/kohei-suzuking)

|資格名|取得年月|
|-----|--------|
|AWS Certified Cloud Practitioner|2020/10|
|ORACLE MASTER 9i Silver (失効)|2003/01|
|XMLマスター:ベーシック|2003/01|

近日試験予定: AWS Certified Solutions Architect – Associate

## 自然言語

|言語|レベル|
|-----|-----|
|日本語|ネイティブ、資格は特になし|
|英語|オフショア開発経験(バングラデシュ、フィリピン、ベトナム、中国など) 2016/07~<br>Hearing: ミーティングでの簡単なヒアリング程度<br>Speaking: 実務で使えるレベルではない<br>Reading: 技術系のドキュメントであれば原文でも活用できる程度<br>Writing:チャットでのやりとりや簡単なドキュメント作成ができる程度|

## 実務経歴(新しい順)

### 2019/09 - 現在 : フリーランス

職務: Webアプリケーションエンジニア(テックリード)

#### Auth0導入支援

<details>
  <summary>案件詳細</summary>

- Auth0を利用した認証・認可システムの導入支援(初期設定等の基盤構築も担当)
- パスワードレス認証、ソーシャルログインの導入や各種APIの使用方法サポートなど
- CI/CDとCLIによる各環境へのオートデプロイ
- メンバー: 3名
- その他: Auth0, SendGrid, Twilio, GitLab, Docker
</details>

#### LINEを利用したマーケティングツールの開発

<details>
  <summary>案件詳細</summary>

- LINE APIを利用したASPサービスの開発(PCのみ、SPA)
- 数百万人規模のユーザーへの配信を想定したバッチ設計が必要だった
- フロントエンドはSPA、バックエンドはREST APIでSwaggerを用いてフロントエンドとのコミュニケーションを行った
- テックリードとして要件定義、設計(アプリケーション、インフラ)、バックエンドの基盤構築、レビューを担当
- 詳細設計、プログラミング、単体〜総合テストはオフショア(フィリピン)で行い、全てのレビューを担当
- メンバー: 5名
- フロントエンド: React 16.x
- バックエンド: Spring Boot 2.2.x(Java 8), Node.js 10.x(AWS Lambda), MySQL 5.7.x(Amazon Aurora)
- その他: AWS, GitLab, Docker
</details>

#### カラオケアプリのリニューアル開発

<details>
  <summary>案件詳細</summary>

- カラオケ練習アプリのREST API開発
- ネイティブアプリ自体の開発は他ベンダーが担当して私のチームはお気に入りや履歴などのパーソナルデータ管理を担当
- バックエンドはREST APIでSwaggerを用いてネイティブアプリとのコミュニケーションを行った
- リニューアルのため既に数十万人のユーザーがおりAPIのパフォーマンスを考えた設計、レビューを行った
- テックリードとして要件定義、設計(アプリケーション、インフラ)、バックエンドの基盤構築、レビュー、負荷テストを担当
- 詳細設計、プログラミング、単体テストはオフショア(フィリピン + バングラデシュ)で行い、全てのレビューを担当
- メンバー: 5名
- バックエンド: Spring Boot 2.2.x(Java 11), MySQL 5.7.x(Amazon Aurora)
- その他: AWS, GitHub, Docker, JMeter
</details>

#### ポイントサイトの横断比較サービスの開発

<details>
  <summary>案件詳細</summary>

- 各種ポイントサイトの案件を横断的に比較できるサービスの開発(PC・スマホ対応のレスポンシブデザイン、SPA)
- Window関数を使用するため初めてのMySQL 8.0を使用した開発だった
- 特にポジションは決まってはなくオフショア(フィリピン)メンバーと共にタスク分担をして全ての工程を担当
- メンバー: 7名
- フロントエンド: React 16.x
- バックエンド: Express 4(Node.js 10.x) Java 8 + Node.js 10.x(AWS Lambda), MySQL 8.0.x(Amazon RDS)
- その他: AWS, GitLab, Docker
</details>

### 2016/06 - 2019/08: 株式会社M(自社開発、受託開発及びSES)

職務: Webアプリケーションエンジニア(テックリード)

#### 居抜き物件売買サイトの開発

<details>
  <summary>案件詳細</summary>

- チャットを利用した居抜き物件売買サイトの開発(PCのみ、SPA)
- 非公開物件のみだったため写真などの情報が関係者以外閲覧できないなどの設計が必要となった
- フロントエンドはSPA、バックエンドはREST APIでSwaggerを用いてフロントエンドとのコミュニケーションを行った
- テックリードとして要件定義、設計(アプリケーション、インフラ)を担当
- 詳細設計、プログラミング、単体〜総合テストはオフショア(バングラデシュ)で行った
- メンバー: 10名
- フロントエンド: Angular 6.0(TypeScript)
- バックエンド: Spring Boot 1.5.x(Java 8), MySQL 5.7.x(Amazon RDS)
- その他: AWS, GitHub, CircleCI, SendGrid, New Relic(APM, Infrastructure)
</details>

#### 駐車場シェアリングサービスの開発・運用

<details>
  <summary>案件詳細</summary>

- 空き地などを利用した駐車場シェアリングサービスの開発(PC・スマホ対応のレスポンシブデザイン、SPA)
- 予約管理やStripeを利用した決済の開発、位置情報を使ったDBの検索など幅広い知識を使った設計が必要だった
- フロントエンドはSPA、バックエンドはREST APIでSwaggerを用いてフロントエンドとのコミュニケーションを行った
- テックリードとして要件定義、設計(アプリケーション)、詳細設計、結合、総合テストを担当
- プログラミング、単体テストはオフショア(バングラデシュ)で行った
- メンバー: 20名
- フロントエンド: Angular 2.0(TypeScript)
- バックエンド: Spring Boot 1.5.x(Java 8), MySQL 5.7.x(Amazon RDS)
- その他: AWS, GitHub, CircleCI, SendGrid, Stripe, New Relic(APM)
</details>

#### その他、他プロジェクトサポート

- PHP全般のサポート
- インフラ構築のサポート
- SQLチューニングのサポート
- 新規プロジェクトのアーキテクチャレビューなど

### 2009/03 - 2016/05: フリーランス

職務: Webアプリケーションエンジニア

#### リワード広告サービスの開発・運用

<details>
  <summary>案件詳細</summary>

- リワード広告を掲載するポイントサイトの開発(スマホのみ)
- ブースト広告が流行っていた時期でもあって常にスパイクアクセスを意識しないといけなく厳しいレビューが必要だった
- 主にバックエンドが中心で要件定義からテストまで全てを担当
- メンバー: 8名
- フロントエンド: jQuery, Handlebars
- バックエンド: CodeIgniter 2.x (PHP 5.6), MySQL 5.6.x, TokyoTylant, Go
- その他: オンプレ, GitHub, Vagrant(+Chef), Jenkins
</details>

#### 通信キャリアのポイントサイトの開発・運用

<details>
  <summary>案件詳細</summary>

- 通信キャリアのポイントサイトの開発(スマホのみ)
- 通信キャリアのサービスのためファーストリリースから数百万人以上のユーザーが利用するのでテストや運用保守が大変なものだった
- 主にバックエンドが中心でプログラミングからテストまで全てを担当
- メンバー: 12名
- フロントエンド: jQuery
- バックエンド: Yii 2.0.x (PHP 5.6), MySQL 5.6.x, memcached
- その他: AWS, GitHub, Vagrant(+Chef)
</details>

#### 各種決済サービス統合システムの開発

<details>
  <summary>案件詳細</summary>

- 各自社サービスごとに開発していた決済を1つの決済システムに統合するプロジェクト(PC、スマホ)
- クレジットカード、通信キャリア決済、WebMoney, BitCash, プロバイダ決済など
- 要件定義からテストまで全てを担当
- メンバー: 3名
- フロントエンド: jQuery
- バックエンド: オレオレフレームワーク (PHP 5.5), MySQL 5.6.x, memcached, Redis
- その他: オンプレ, Subversion
</details>

#### 競馬サイトの開発・運用

<details>
  <summary>案件詳細</summary>

- 競馬サイトのSNSや掲示板などを中心に開発(PC、スマホ)
- 大レース時にはスパイクアクセスがあるためそれを意識した開発が必要だった
- 主にバックエンドが中心で要件定義からテストまで全てを担当
- メンバー: 8名
- フロントエンド: jQuery
- バックエンド: オレオレフレームワーク (PHP 5.4), MySQL 5.5.x, memcached, Redis
- その他: オンプレ, Subversion
</details>

#### 競馬ゲームの開発・運用

<details>
  <summary>案件詳細</summary>

- 競馬のブラウザーゲームの開発(ガラケー、スマホ)
- 自社ガラケーサイト(3キャリア)、自社スマホサイト、mobage、GREEなどで配信
- 詳細設計からテストまで全てを担当
- メンバー: 5名
- フロントエンド: jQuery
- バックエンド: オレオレフレームワーク (PHP 5.3), MySQL 5.5.x, memcached, Kumofs
- その他: オンプレ, Subversion
</details>

### 2006/10 - 2009/02: 株式会社S(受託開発及びSES)

職務: Webアプリケーションエンジニア

#### 映画サイトのリニューアル開発

- 省略

#### 確定拠出年金管理システムの開発

- 省略

#### 補助金交付申請システムの開発

- 省略

### 2004/02 - 2006/09: 株式会社N(自社開発)

職務: Webアプリケーションエンジニア

#### 競馬サイトの開発・運用

- 省略

#### CMSの開発

- 省略

### 2001/03 - 2004/01: S株式会社(受託開発及びSES)

職務: Webアプリケーションエンジニア

#### 主にNECや富士通などの電機メーカーのWebシステム開発・運用

- 省略
