# CloudNative Days Tokyo 2021 Co-located Event Handson 概要

この度は、『OCHa Cafe Presents★Kubernetes & オブザーバビリティ 入門ハンズオン』へのご参加、誠にありがとうございます。

タイムテーブル、資料などは、以下となります。

## タイムテーブル

2021.11.2

| 時間 | 概要 |
| --- | --- |
| 13:50 | Zoom接続開始 |
| 14:00 | Opneing |
| 14:05 | Oracle Container Engine for Kubernetes(OKE)の紹介 |
| 14:20 | Observabilityについて（ハンズオン概要含む）|
| 15:00 | Q&A(セッション) |
| 15:05 | 休憩 |
| 15:10 | ハンズオン(適宜休憩取ります) |
| 17:20 | Q&A(全体) |
| 17:30 | Closing |

※時間は若干前後する可能性があります。

## コミュニケーションガイド

### 1.セッションに関する質問

「Q&A(セッション) 」時にまとめてお答えします。Zoomチャット、口頭の場合はマイクをオンにしてお願いします。

### 2.ハンズオン時の質問

Zoomチャット、口頭の場合はマイクをオンにしてお願いします。場合によってはブレイクアウトルームでの対応も行います。

### 3.運営事務局に対する連絡

音声・画像の不具合や運営に関するものは、Zoomチャットでお願いします。

## ハンズオンテキスト

以下のハンズオンテキストをベースに、講師と共に実施します。

[『Oracle Container Engine for Kubernetes(OKE)でサンプルマイクロサービスアプリケーションをデプロイしてオブザバビリティツールを利用してみよう』](https://oracle-japan.github.io/ocitutorials/cloud-native/oke-for-advances/)

ハンズオンテキストにある【オプション】の2項目については、ハンズオンとしては進行状況に応じて対応します。

### 注意事項

上記ハンズオンテキストで、本ハンズオンで一部、読み替える箇所があります。  
以下記載します。

* 「3-2 サンプルアプリケーションのビルドとデプロイ」

ここで記載されている、docker build作業は、本ハンズオンでは説明は行いますが割愛します。

* 「5-1 動的グループとポリシーの設定」

動的グループの設定する名前と説明は、本ハンズオンでは「grafana_dynamic_group」で問題ありません。

ポリシーで設定するを行う場合、記載通り、以下で問題ありません。

`allow dynamic-group grafana_dynamic_group to read metrics in compartment id <ご自身のコンパートメントOCID>`

* 「5-3 Grafanaダッシュボードの確認」

設定する「Default Region」は、本ハンズオンでは「ap-osaka-1」ではなく、「us-ashburn-1」とします。

「ご自身のコンパートメント名」は、「root compartment」を指定してください。

* 「6-1 ポリシーの作成」

本ハンズオンでは、このポリシー作成は不要です。次に進んでください。

### 削除処理

ハンズオンテキストを実施後、削除処理を行わなくても、OCIのトライアル環境のため課金は発生しません。  
30日間、有効に使用するために削除処理の手順も記載しておきます。

[削除処理](https://github.com/oracle-japan/ochacafe-cndt2021-handson/blob/main/README2.md)

## スライド資料

セッションで利用したスライド資料は、以下にアップロードしています。

* [Oracle Container Engine for Kubernetes(OKE)の紹介](https://speakerdeck.com/oracle4engineer/oracle-container-engine-for-kubernetes-oke-goshao-jie)

* [Observabilityについて](https://speakerdeck.com/oracle4engineer/observabilitynituite)

## アンケート

今後の改善に努めたいと思いますので、アンケートのご協力をお願いします。

[アンケートフォーム](https://bit.ly/1102-ocha)

## Oracle Cloud Hangout Cafe について

[Oracle Cloud Hangout Cafe](https://ochacafe.connpass.com/)、略してOCHa Cafe（おちゃかふぇ）です！

ハッシュタグ: #ochacafe

Oracle Cloud Hangout Cafeは、クラウドネイティブ時代の開発者を対象に巷で話題のオープン・スタンダードなテクノロジーをテーマに取り上げ、短時間でガッツリ学んでお持ち帰りいただくテクニカルな勉強会シリーズです。

本ハンズオンは、この勉強会シリーズの番外編です。

知識習得やスキル向上の場として是非ご活用ください！

また、スピン・オフ企画として、不定期に「OCHaCafe Premium」も開催しています。通常版はOracle固有な話題にならないテーマを扱いますが、PremiumではOracle Cloudにフォーカスし、Oracle Cloud実践のための情報をお届けします。

