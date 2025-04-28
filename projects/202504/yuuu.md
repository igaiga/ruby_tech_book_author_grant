次のような本を執筆したいと考えています。

# 執筆予定内容の説明

## タイトル

MQTTクライアントを作りながら学ぶソケットプログラミング入門

## 概要

本書はソケットプログラミングの入門書です。お題としてMQTTクライアントを作成します。
まずはRubyのSocketクラスを使ってソケットプログラミングの流れを学び、後半ではC言語を使って同様のプログラミングを行います。
「Rubyは読めるものの、もっと低いレイヤに触れてみたい」という読者にぴったりな1冊を目指します。

## 対象読者層

以下のいずれか1つにでも該当すれば対象読者になり得る想定です。

- ネットワークやソケットプログラミングに興味がある人
- MQTTについて学びたい人
- 既にRubyを学んでいて、実践的なプログラミングに挑戦したくなった人
- C言語に興味がある人

## 読者が習得できる技術

- ソケットプログラミング
  - TCP/IPによる通信を抽象化したインターフェースである「ソケット(Socket)」を用いたプログラミングの手法を習得できます
  - Wiresharkを用いたパケットキャプチャの手順についても解説します
- MQTT
  - IoTのような、組み込み機器がインターネットを介してクラウドと通信するシステムにおいて使用される、MQTTという通信プロトコルの仕組みを学べます
  - mosquittoやMQTTXといったOSSのMQTTクライアントの使い方についても解説します
- Ruby、C言語
  - 本書ではRubyとC言語によるソースコードおよび解説を記載しており、実践的なプログラミング手法を学べます

## 目次

1. メッセージングプロトコル: MQTT
  - MQTTとは
  - MQTTで通信をする際の登場人物
  - MQTT通信の流れ
2. 開発に使用するツール
  - Rubyの開発環境
  - C言語の開発環境
  - MQTTブローカー
  - MQTTクライアント
  - パケットキャプチャ
3. ソケットプログラミング入門
  - TCP/IPの概要
  - 通信の流れ
  - echoサーバーを書く
4. クライアント開発(Ruby編)
  - MQTT Connectをする
  - MQTT Publishをする
  - MQTT Subscribeをする
5. クライアント開発(C言語編)
  - MQTT Connectをする
  - MQTT Publishをする
  - MQTT Subscribeをする
6. おわりに

## 著者プロフィール

株式会社FusicのIoTクラウドエンジニア。山口県出身、福岡県在住。
組み込みシステムの開発を7年ほど経験し、Web/クラウドを扱う現職に転職後、IoTシステムの受託開発を担当している。
フィヨルドブートキャンプのメンターを担当し、レビューや日報を通じてRubyの学習者をサポートする。
2024 Japan AWS Top Engineers、RubyKaigi 2025 Speaker。

# 過去に執筆した文章や書籍など

- [AWSとM5StickCで作るIoT開発入門](https://techbookfest.org/product/5189029702139904)
- [作って学ぶSORACOM入門](https://techbookfest.org/product/5273269798174720)
- [AWS Amplifyで作るIoTバックエンド](https://techbookfest.org/product/ph4YMFR31tnMxEnWrba0Wd)
- [AWSとRubyではじめるサーバーレス入門](https://techbookfest.org/product/srni2eQTAKXY59aVTFRSag)
- [生活をちょっと便利にするIoTボタンのつくりかた](https://techbookfest.org/product/rwkYYevZRmhdfFGBksTeMk)
