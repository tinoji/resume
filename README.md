tinojiの職務経歴書
======
[@tinoji](https://github.com/tinoji)の職務経歴やスキルなどをまとめたページです。

<br>

基本情報
-------
|Title|Value|
|---|-----|
|氏名|菊地 弘晃(きくち ひろあき)|
|生年月日|1992年1月18日|
|性別|男|
|連絡先|MessengerかTwitterで連絡ください。|

<br>

SNS
-------
|Name|URL|
|---|-----|
|Twitter|https://twitter.com/_tinoji|
|Facebook|https://www.facebook.com/hiroaki.tinoji.kikuchi|
|Lapras|https://lapras.com/public/DA4JKIN|
|Qiita|https://qiita.com/tinoji|
|Zenn|https://zenn.dev/tinoji|
|Speaker Deck|https://speakerdeck.com/tinoji|
|note|https://note.com/tinoji|

<br>

職務経歴(本業)
-------
### 合同会社DMM.com
【期間】2017/04 - 現在
【事業内容】各種インターネットサービス業など
【当時の社員数】約3000人

#### 所属・役職
- 2017/8 - 現在: 動画配信事業部 配信基盤チーム Webエンジニア

#### 主なプロジェクト
|プロジェクト|期間|言語|利用技術|役割|メンバー|内容|
|---|-----|-----|-----|-----|-----|-----|
|無料動画システムのリプレイス|2021/05-|Lua|GCP(GKE, Memorystore), Kurbernetes|エンジニア|4人|レガシーシステムのリプレイスを行っています。GCP環境構築、GKEを利用したAPI開発を主に行いました。|
|ブラウザ動画プレイヤー開発・UI/UX改善|2020/09-2021/06|JavaScript, HTML, CSS, PHP||エンジニア、開発リーダー、要件定義|3人|DMM動画のPCブラウザプレーヤーに視聴率グラフ、倍速機能などの新機能を実装しました。また、設定メニュー、アクセシビリティ、画質表記などのUI/UX改善を行いました。|
|ジョブスケジューラのクラウド移行|2020/01-2020/08||Rundeck, GCP(GKE), AWS(RDS, S3), Kubernetes|エンジニア|2人|オンプレのジョブスケジューラをGKEに載せ替え、可用性・耐障害性の向上を図りました。|
|電子書籍配信キャッシュサーバの開発|2019/09-2019/10|Lua|nginx(OpenResty), Consul, Ansible|エンジニア|1人|OpenRestyとConsul KVを利用してミニマルで低コストなキャッシュサーバを実装しました。|
|AWSを利用したライブ配信システムの構築|2019/09-2020/01||AWS(Media Services, CloudFront, CloudFormation)|エンジニア|~3人|AWS上に大規模なライブ配信を行えるスタックを構築し、IaC化を行い配信イベント等で即座に対応できるようにしました。最も規模の大きいものではUUが117,000人、同時接続数62,000の配信イベントで利用されました。|
|動画プレイヤーE2Eテスト|2019/03-2019/05|Java(Groovy)|Katalon Studio, CircleCI, Jenkins|エンジニア|1人|動画プレイヤーのリリース前検証・定常的なヘルスチェックのためにE2Eテストを作成しCI/定期実行する仕組みを構築しました。|
|動画分散エンコードシステムの開発|2018/10-2019/12|C#(.Net Core), Go, Python|Ansible, Rundeck|エンジニア|~10人|動画のエンコードを高速・低コストで行うためのシステムを開発しました。主に配信ストレージへのアップロード、DRMパッケージング、配信メタデータ処理、サムネイル作成、バックアップ・ディザスタリカバリ設計などを担当しました。 システム概要については[こちらの記事](https://inside.dmm.com/entry/2020/03/19/evolving_content_delivery_platform_07)を参照。
|動画の同時視聴制限機能の開発|2018/11-2019/05|Go, JavaScript, Kotlin|GCP(GAE, Datastore, Terraform)|エンジニア、開発リーダー、要件定義|~10人|GAE/Goを利用してAPIを実装したほか、PC動画プレイヤーとFireTV/AndroidTVアプリの実装を行いました。|
|動画プレイヤークライアントサイドログの開発|2018/11-2019/05|JavaScript, Kotlin||エンジニア、開発リーダー、要件定義|~10人|動画プレイヤーの詳細な再生ログを収集するための設計・開発を行いました。|
|VR動画高画質化|2018/08-2018/10|Lua, PHP|nginx(OpenResty)|エンジニア、チーム間渉外、スケジュール管理|~25人|配信データを処理するAPIの実装に加えてチーム内のスケジュール管理やディレクションを行いました。|
|VR動画のミドルレンジAndroid端末対応|2018/01-2018/09|Lua|nginx(OpenResty)|エンジニア|~8人|スペック不足でVR動画の再生ができていなかったAndroid端末でもVR動画が再生できるように新しい画質の配信を開始しました。主にSoC調査とAPI実装を担当しました。|
|画像動的リサイズキャッシュサーバの開発|2017/11-2018/07|Lua, Go, Ruby(Ruby on Rails)|Redis, Redis Sentinel, Ansible, Consul|エンジニア|2人|画像のリサイズやクロップ処理を行えるキャッシュサーバに新機能やロギング処理を実装しました。またキャッシュ情報を管理するサーバや社内用の管理画面の実装、KVSのリプレイスなどを行いました。|
|チームの開発環境・デプロイ基盤・通知基盤の構築|2017/08-2018/02||Proxmox, Rundeck, Huginn, SonarQube、Ansible|エンジニア|1人|LXC/VM開発環境の構築、ジョブスケジューラと構成管理ツールを利用したデプロイ基盤の構築、通知基盤の構築、コードの品質管理ツールの構築・運用。|

<br>

#### その他の取り組み
##### 採用
- リファラル会食
    - リファラル会食制度ができた際に率先して活用し、4ヶ月間で約50人(主に学生さん)と接触しました。
- 採用チャネル開拓
    - 大学サークル・学生コミュニティ4団体と新たにイベントや会食を開始、継続的に接触を続けています。
- AtCoder活用の提案
    - 新卒採用にAtCoderのコンテスト主催やAtCoder Jobsの利用を提案。
    - 上記は叶いませんでしたがサポーターズ社のAtCoderコラボイベントへの参加に繋がり、自身も参加しました。
- 採用資料レビュー・コンサルティング
    - 主にリスク回避を目的として人事部の外部資料をレビューし、アドバイスを行いました。

##### 社内エバンジェリスト
- SRE文化の導入
    - インシデントドキュメント、ポストモーテム、SLOの概念をチームに導入し、定着するまで運用を行いました。
- コードの品質管理
    - コードの品質管理ツール(SonarQube)の導入を行い、全社的に活用してもらえるようにドキュメント・ルールの整備を行いました。
    - 比較的サイズの大きい(300万行程度)リポジトリに導入し、1ヶ月程度でバグ判定数を305個から0個まで減らしました。

##### その他
- DMM WEBCAMP web広告にモデル出演

<br>

職務経歴(副業)
-------
### 株式会社MINT STUDIO
【期間】2021/08 2週間程度
【事業内容】インターネットビジネスの企画・開発・マーケティング
【当時の社員数】2人

#### プロジェクト
|プロジェクト|期間|言語|利用技術|役割|メンバー|内容|
|---|-----|-----|-----|-----|-----|-----|
|新規事業リサーチ|2021/08|N/A|N/A|技術リサーチ、事業提案|1人|新規事業の技術的な実現可能性調査・検証。|

<br>

### 株式会社アダコテック
【期間】2019/09 - 2020/12
【事業内容】工業製品の検査・検品自動化、生産設備の異常検知、社会インフラの検査・異常検知
【当時の社員数】〜10人

#### プロジェクト
|プロジェクト|期間|言語|利用技術|役割|メンバー|内容|
|---|-----|-----|-----|-----|-----|-----|
|[製造業向け機械学習SaaS](https://adacotech.co.jp/news/2402)の開発|2019/09 - 2020/12|Python|Flask, AWS(ECS, RDS)|エンジニア|~10人|立ち上げからジョイン。技術選定、サーバーサイド設計、開発、テスト。|

<br>


登壇
-------
|Date|Event|Type|Slide|
|---|---|---|---|
|2019/6/12|[Media-JAWS #2](https://media-jaws.doorkeeper.jp/events/91677)|セッション(10分)|[VODのディザスタリカバリをAWSで考えてみる](https://speakerdeck.com/tinoji/vodfalsedeizasutarikabariwoawsdekao-etemiru)|
|2019/4/24|[Media-JAWS #1](https://media-jaws.doorkeeper.jp/events/89643)|LT(10分)|[ちょっと冷や汗かいたけどAWS MediaLiveは最高！って話 - Speaker Deck](https://speakerdeck.com/tinoji/tiyotutoleng-yahan-kaitakedoaws-medialivehazui-gao-tutehua)|
|2018/12/17|[第4回 HashiCorp User Group Meetup](https://hashicorp.connpass.com/event/110653/)|セッション(20分)|[DMM動画の可用性を支えるConsul - Speaker Deck](https://speakerdeck.com/tinoji/dmmdong-hua-falseke-yong-xing-wozhi-eruconsul)|

<br>


執筆
-------
|Date|Article|
|---|---|
|2019/5|[慶應義塾大学KCSxDMM 合同LT会レポート](https://inside.dmm.com/entry/2019/05/22/kcs-dmm-lt)|
|2018/10|[DMM動画サービスの問題を解決しようとしている話（再生URL生成API編）](https://inside.dmm.com/entry/2018/10/17/create-playurl)|

<br>


取材記事など
-------
|Date|Article|
|---|---|
|2020/1|[よんでますよ、野秋さん #4 (対談)](https://inside.dmm.com/entry/2020/01/23/yondemasu04)|
|2019/7|[Media-JAWSで聞いた視聴者参加型コンテンツとVODの災害対策](https://ascii.jp/elem/000/001/893/1893281/)|

<br>


スキル・経験
---------
:point_right: [スキルリスト](/skills.md)

<br>


資格など
-------------
|Certification|Certificate|
|---|---|
|Google Cloud Professional Cloud Developer|[Link](https://www.credential.net/rbcqalqj?key=6f5f55cc13928d328ea559bc0f5aec9d2be1104a14d13295addec1e13a667dba)|
|Developing Applications with Google Cloud Platform (Coursera Specialization)|[Link](https://www.coursera.org/account/accomplishments/specialization/669HPPL75RD5)|
|Machine Learning (Coursera Course)|[Link](https://www.coursera.org/account/accomplishments/verify/EDCWDNN9AHNJ)|
|基本情報処理技術者|第FE-2015-10-11665号|
|日商簿記検定試験 3級|144の3第23704|
|Oracle Certified Java Programmer, Bronze SE 7/8|249061807BRZSE78JPN|
|TOEIC total score: 830||

<br>


学歴/研究
--------
### 2015/04 - 2017/03 京都大学農学研究科 森林科学専攻 生物繊維学研究室
- 修士論文
    - 『in-situ 磁場配向を用いたタンパク質微結晶のＸ線単結晶構造解析』
- 受賞
    - 2016年11月，第11回日本磁気科学会年会 ポスター賞
- 学会発表
    - 2015年10月，日本結晶学会年会，ポスター発表 PB-009
    - 2015年10月，日本結晶学会年会，口頭発表 17-OB-06
    - October 2015, International Conference on Magneto-Science, Oral Presentation 2O05
    - June 2016, 15th European Powder Diffraction Conference, Oral Presentation MS03-O3
    - 2016年11月，第11回日本磁気科学会年会，ポスター発表 P-13
    - November 2016, International Workshop on Recent Progress of Magneto-Science, International Session I-03
    - March 2017, BIT's 5th Annual Conference of AnalytiX
- その他
    - 大型放射光施設SPring-8 2016年大学院生提案型課題採択，課題番号：2016A2698/2016B2698


### 2011/04 - 2015/03 京都大学農学部 森林科学科
- 投稿論文
    - [Crystal System Determination from X-ray Diffraction of Magnetically Oriented Microcrystal Suspensions](https://pubs.acs.org/doi/abs/10.1021/cg501357b)
- その他
    - 2014年8月, 世界結晶年 対称性・群論トレーニングコース修了 ＠高エネルギー加速器研究機構
    - 意識高い系こじらせて余剰単位43取った。

<br>


趣味・好きなもの
-------------
- ラジオ
- 二郎系
- 温泉・銭湯
- 坂道グループ
- 登山
