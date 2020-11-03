# オープン職務経歴書

本オープン職務経歴書について、作成の経緯などを以下記事にまとめてあります。

[話題のオープン職務経歴書を書いてみる](https://qiita.com/Sa2Knight/items/4af2f24fac9290d26119)

## 転職活動ステータス

**積極的な転職活動を行うつもりはないが、技術的なキャリアアップについてお悩み中** (2020/07/27 更新)

## 基本情報

|key|value|
|----|----|
|Name|笹木 信吾|
|Birth(Age)|1992/05/29(28)|
|Family|既婚・子なし|
|Location|東京都 墨田区|
|Education|地方駅弁の情報系学部|
|Mail|shingo.sasaki.0529@gmail.com|
|Twitter|[@s_sasaki_0529](https://twitter.com/s_sasaki_0529)|

## アウトプット

### 登壇資料

- [TeachmeBizを支えるフロントエンドのアーキテクチャと品質担保](https://www.slideshare.net/shingosasaki3/teachmebiz-188542240) (Vue.jsアーキテクチャリング勉強会)
- [レガシーすぎるRailsアプリを10倍高速化した組織的なカイゼン活動](https://www.slideshare.net/shingosasaki3/rails10-135067544) (表参道.rb #44 〜Ruby/Railsパフォーマンス〜)

### ブログ

- [個人ブログ](https://shingo-sasaki-0529.hatenablog.com/)
- [Qiita](https://qiita.com/Sa2Knight)
- [所属会社の開発ブログ](https://medium.com/@shingo.sasaki) (リンク先は私が書いた記事リスト)

## 労働環境に関する主な希望

- 技術力向上がしやすい環境
  - 技術力向上に対する意欲の高い人が多い
  - 幅広い分野の技術で相談できる人がいる
  - 書籍購入費、勉強会参加費、資格試験費などがある程度補助される
  - 社内勉強会、LTなど
- モダンな開発
  - ドキュメントの整備
  - テスト重視(TDD/CI)
  - モダンな技術/ツールの活用
  - コードレビュー/プルリク
  - アジャイル
- 自分のペースで働ける
  - フレックス制度 (コアタイム短め)
  - リモートワーク
- 自分の慣れた開発環境
  - ハイスペックマシン(Mac/Linux)
  - エディタ選択の自由(vscode or vim)
  - モニタ複数枚
  - メカニカルキーボード
- 評価基準が透明
  - 期待しているもの、期待されてるものが明確
  - 目標設定に依存しないこと
- 残業なし

## 資格

|資格名|取得年月|
|-----|--------|
|ITパスポート|2010/11|
|基本情報技術者|2012/05|
|応用情報技術者|2013/06|
|情報セキュリティスペシャリスト|2014/06|
|ネットワークスペシャリスト|2014/12|

IPA資格は全て学生時代に取ったきり。社会に出てからは、資格より経験積むほうが大事だと実感

## 自然言語

|言語|レベル|
|-----|-----|
|日本語|ネイティブだけど資格は特になし|
|英語|TOEIC L&R 775点(2019/11)|

英語は技術系のドキュメントならまぁ原文でも活用できる程度

## プログラミング言語/フレームワーク

|言語/フレームワーク|経験レベル|
|----|----|
|Rails(Ruby)|設計から実装までチーム引っ張れる|
|Vue(js)|設計から実装までチーム引っ張れる|
|React(js)|実務で軽量アプリ開発に使ったことがある程度|
|jQuery(js)|実務でそれなりに使ってた|
|Laravel(PHP)|過去に設計から実装までやったことあるので思い出せば使える|
|Sinatra(Ruby)|実務で簡易的なAPIサーバ作った|
|Bottole(Python)|実務で簡易的なAPIサーバ作った|
|Wordpress(PHP)|実務でWebアプリ用のテンプレートを仕様を元に実装したレベル|
|Swift3|実務で簡易的なカメラと、写真共有アプリを実装した|
|Perl|新卒入社した会社でガッツリ使ってたけど何も覚えてない|
|TypeScript|趣味でちょっと|
|Go|趣味でちょっと|

## 実務経歴(新しい順)

### 3社目 某BtoB SaaSベンチャー (2018/08 ~ 現在)

#### 概要

- よりモダンでレベルの高い開発経験を得るために転職
- BtoB SaaSの開発保守運用
- 主にRails/Vueの構成で、概ねモダンな開発スタイルを採用している

#### プロジェクト

- スクラム開発経験(スクラムマスターではない)
- RailsによるRESTっぽい新規APIの設計、実装
    - rspecによる単体テスト、リクエストテストの作成
    - apiblueprint/aglioによるAPIドキュメントの作成
    - Elasticsearchによる検索最適化
      - インデックス再定義の検討、ダウンタイム無しでのインデックス張替え
      - 効率の良い検索クエリの検討、実装
- VueJSによるフロントエンドの設計、実装
  - storybookによるUIコンポーネントのカタログ化
  - vue-test-utilによるVueコンポーネントの単体テストの提案、実装
- 各種AWSを活用した機能開発(インフラ構築ではない)
  - Amazon Redshift上にあるログを元に集計をユーザに提供する機能の開発
  - AWS Redshift/S3/Auroraを活用したサマリーの生成周りの設計、実装(補助)
  - terraformによるAWSリソースのコード化
- CI/CDの管理
  - CircleCIによるCIの継続的改善活動
  - ステージング環境への任意のブランチの自動デプロイの仕組みの実装
  - Storybookとreg-suitを用いたUIのスナップショットテストの提案、実装、運用
  - CapybaraによるE2Eテストの提案、設計、実装、運用
  - Slackコマンドによる開発プロセスの自動化促進(テスト実行、ステージングデプロイ)
  - 他、CIの設定構成の管理全般
- ライブラリバージョンの管理と積極的な改善
  - 自動バージョンアップの自動化(gem/node_modules)
  - Webpack3からWebpack4へのアップグレード
  - レガシー化したフロントエンドビルド環境のアップグレード
    - node 8.x → 12.x
    - Webpack 3 → 4
    - vue-loader 14 → 15
    - ...etc

### 2社目 受託開発及びSESの会社 (2016/10 ~ 2018/07)

#### 概要

- 幅広い技術を使った開発経験を得るための転職
- 短いサイクルでの受託開発をしていた時期と、SESで客先常駐した時期がある

#### プロジェクト

- BtoBマッチングサイト
  - Backbone/Marionette)によるSPAの開発
  - PHP(Laravel)を用いたAPIサーバの実装
  - node(socket.io)による双方向リアルタイムチャット機能の実装
- WordPressによる地域密着型マッチングサイトの開発
  - WP案件デビュー
  - はじめての自動テスト(PhantomJS/CasperJSによるE2Eのみ)
- 写真共有系サービスの開発
  - Swiftによる、はじめてのゼロベースでのメイン実装を担当
  - カメラ制御周りの実装
  - PHP(Laravel)を用いたAPIサーバの実装
  - PHPUnitによる機能テストの実装
  - フロントエンドはVueにして半SPAに
- OpenStackによる汎用インフラ構築ツールの開発
　- 短期の客先常駐
  - 概ね出来上がっているインフラ構築ツールの終盤の実装作業を担当
  - OpenStackを用いたクラウド環境構築を自動化するための機能の実装
  - JavaScript/PHPによる上記機能を利用するためのWeb画面の実装
- クラウドファンディング系SPAの開発
  - ゼロベースからの開発を担当
  - Ruby on railsによるAPIサーバの実装
  - React/Reduxによるフロントエンドの実装
  - scssによる画面デザイン
  - Redisを用いたキャッシュサーバの構築
  - payjpを用いたクレジットカード決済機能の実装
  - SendGridを用いたメール配信機能の実装
- Wordpressによる製品マニュアル閲覧サイトの開発
  - 既にコンテンツ部分が出来上がっているサイトに対するロジックの追加を担当
  - Dockerを用いた開発環境の構築及び配布
  - Wordpressの管理画面の各種カスタマイズ
  - 認証付きのコンテンツダウロード機能の実装
  - 各種統計データのインポート/エクスポート機能の実装
- 機械学習を含む、WordpressによるBtoBのマッチングサイトの開発
  - 機械学習を用いたレコメンド機能の機械学習部分の実装を担当
  - Python(scikit-learn)を用いた機械学習ロジックの実装
  - Python(Bottle)を用いたAPIサーバの実装
  - nginx/uwsgiによるサーバ構築
  - PHPとMediaSMSを用いたSMSによる認証機能の実装
  - APIの各種設計など
- アンケート集計結果の可視化システムのプロトタイプ開発
  - mySQLで管理されたアンケートの集計結果を可視化するWebサービス
  - サーバサイドはLaravelを利用し、APIサーバを実装
  - クライアントサイドはVueを利用し、SPA形式で実装
  - グラフの描画にはChatjsを用いて、Vueと組み合わせてリアルタイムに折れ線グラフ/レーダーチャートを生成する機能を実装
  - 基本的な機能を一通り実装したプロトタイプを提出して終了

### 1社目 某ISP (2015/04 ~ 2016/09)

#### 概要

- 新卒入社で２２年間の東北生活を経ての状況
- ビジネス研修を得て開発部に配属、大学等教育機関向けLMSの開発運用のチームに従事
- 上流から下流までの一通りの経験を得る

#### プロジェクト

- Web系LMSの設計/開発/運用
  - リリースから10年程度の大規模Webサービスの保守運用
  - Perl(自社製フレームワーク)によるサーバサイド実装
  - HTML/CSS/JavaScript(ネイティブ)によるフロントエンド実装
  - Ruby(Sinatra)を用いたAPIサーバ実装
  - SOAPを用いた外部システムとの連携
  - シェルスクリプトを使った開発補助ツールの開発
  - 他、クライアントとの各種打ち合わせ、機能提案(プレゼン)など
- 教育支援ツールのiOS版の追加開発
  - Objective-Cで実装されたリリース済みの既存アプリに対する機能追加、改善を担当
  - Bluetoothを用いた外部ハードウェアとアプリの連携周りの実装

## 趣味

- カラオケ
- デグー飼育
- リングフィットアドベンチャー
- 散歩
