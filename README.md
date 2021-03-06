#職務経歴書
======

##保持スキル

* WEBシステムのインフラ構築/運用
    * サーバ、NW機器の選定、導入
    * Linux（物理、KVM、AWS）を用いた各種サーバの設計、構築、運用
    * L2/L3スイッチ、ルータの設定
* シェルスクリプト/Perl/Rubyなどを使った各種ツール作成
* WEBアプリケーションの開発(PHP)

##資格（全て失効済？）

|資格|取得年|
|:----|-------:|
| TOEIC 720点 | 2008 |
| ソフトウェア開発技術者 | 2007 |
| CCNA、SCSA、ORACLEマスターBRONZE | 2007 |
| LPIC-3 Core | 2008 |
| テクニカルエンジニア（NW）| 2008 |

##学歴/職歴

|年||
|:----|:-------|
| 1996/4 | 香川県立 丸亀高校 入学 |
| 1999/3 | 高校 卒業 |
| 2000/4 | 神戸大学 工学部 電気電子工学科 入学 |
| 2005/3 | 大学 卒業 |
| 2005/4 | 神戸大学 大学院 自然科学研究科 電気電子工学専攻 入学<br>研究対象はモバイル/ユビキタス/ウェアラブル |
| 2007/3 | 大学院 卒業 |
| 2007/4 | 伊藤忠テクノソリューションズ 入社 |
| 2009/5 | 伊藤忠テクノソリューションズ 退職 |
| 2009/6 | CROOZ株式会社（当時WebDoJapan）入社 |
| 2012/9 | CROOZ株式会社 退職 |
| 2012/10 | ナビプラス株式会社 入社 |
| 2014/3 | ナビプラス株式会社 退職 |
| 2014/4 | イタンジ株式会社 入社 |


##職務経歴

####イタンジ株式会社

* 賃貸物件の360度パノラマ画像の表示機能の開発(PHP/JavaScript)
    * 画像のアップロードから物件ヒモ付けまでの管理画面の設計/構築
    * フロントの表示部分の設計/開発
* B向けシステムのインフラの設計構築(AWS)
* C向け賃貸ポータルの各種機能開発(PHP)

####ナビプラス株式会社

* オペレーション
    * 24/365の運用、監視
    * 障害、性能限界に対するOS/MWレベルでの調査と対応
    * PXEブート+kickstartによるOSインストールの自動化
    * chef+githubの導入によるサーバ構築の自動化とバージョン管理
* サーバ構成見直し/インフラコストの削減
    * 仮想化（KVM）、HW構成の調整によるサーバ集約
    * 各コンポーネントごとに論理サーバを分割し、信頼性向上とオペレーションコストを削減
    * 冗長化/バックアップの整備
* 非機能系の開発
    * 管理画面系の開発
    * SQL改善
    * バッチ処理の高速化

####CROOZ株式会社

* 10G対応NW機器の導入
    * 機器選定、検証までを担当
* AWSを使ったUS向けインフラ構築
    * 設計、構築を担当
    * VPCで既存DCと接続し、管理/集計/監視系は既存環境を利用<br>→APP x3、memcache x2、DB(RDS) x3のみの構成でリリース
* 社内無線LANの再構築
    * 外部ベンダと協力しつつ、設計/構築
* 画像の動的生成によるストレージコスト削減
    * 一部案出しとインフラ系作業を担当
* CDN導入
    * 検証、選定、導入を担当
* 社内システムのモバイル対応機能を開発
    * 手が空いてたので開発担当
    * スマフォ対応はjQuery Mobile使ってみました
* DC集約
    * DC選定、移行作業を担当
    * 複数DCに分散していたサーバを1DCに集約
* 社内ルータ、DCルータのリプレース
    * 設計のみ担当
* Mobage向けインフラ構築
    * 検証、導入を担当
    * ポチポチゲームだと更新きつくてMySQLのレプリケーション追いつかなかったのでSSD導入
* インフラ構成、開発フレームワークの標準化
    * インフラ部分、デプロイ部分を担当
* サーバ構築の自動化
    * 検証、導入を週末コソコソ実施
    * 仮想コンソール+PXEブート+kickstartによるOSインストール自動化&リモート化<br>構築手順のスクリプト化<br>ローカルyumレポジトリの構築
* 拠点間VPN構築
    * 検証、導入を担当
* LVSの導入
    * 検証、導入のサブ担当
* iSCSIストレージの導入
    * 検証、導入のサブ担当
* NW冗長化
    * 検証、導入を担当
    * L2、L3スイッチ冗長化、bondingにるNIC冗長化
* 新技術の導入検証
    * SSD/ioDrive等の検証、導入
    * Zabbixの試験導入、各種監視強化
    * Fluentdによる各種ログ収集とグラフ作成
    * TreasureDataを試験導入し
  
####CTC

* 怒られそうなので詳細は省略
* syslog集約サーバのリプレース(Solaris -> Linux) 
* HW監視システムの構築(Linux/SNMP/syslog)
