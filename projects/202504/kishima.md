# 執筆予定内容の説明

## タイトル

Deep Dive into mruby

## 概要

mrubyの言語自身の実装に関する解説書です。コード解説だけでなく、mrbgemの実装方法も含めて応用方法についても解説する予定です。

本書はもともとmruby2.0をベースに「[mrubyバイトコードハンドブック](https://silentworlds.info/2019/05/26/post-751/)」として執筆したものを、最新のmruby3.4に合わせて全面改訂しつつ、バイトコード以外のVMの実装および、mrubyの実装全体についても説明を拡充したものです。

「mrubyバイトコードハンドブック」については、コアなmrubyユーザさんからmruby最新版に合わせた改訂をしてほしいと過去にリクエストされていたのですが、なかなか手がつかなかったものを、この機に形にしたいと考えています。

mrubyの言語実装としての解説書はあまりないので、きっと本書の内容を必要としてくれる方がいるはずと考えています。

また本書によって、mrubyの応用例がさらに広がってほしい、というのも本書執筆のモチベーションとなっています。

本書は年末ごろのBOOTHでの販売を予定しています。タイミングが合えば技術書典での頒布も検討したいと考えています。

## 対象読者層

mruby中級～上級者向け。
mrubyの仕組みを理解して、改造や独自の拡張をしたい人

## 読者が習得できる技術

本書を読むことで、mrubyの言語としての仕組みが分かり、もしCRubyの言語実装に詳しい方が読めば、CRubyとの違いについても、より正確に理解してもらえる内容だと考えています。

mrubyは言語実装のコンパクトさ、ポータビリティの高さも特徴ですが、
本書の知識を理解することにより、mrubyを特別な組み込みソフト環境に移植したり、自身のアプリケーションにDSLとして取り込む際の作業の助けになるはずです。


## 目次

```
第1章 本題の前に
1.1 本書の⽬的
1.2 mruby とは
1.3 mruby の基本的な動き
1.4 本書の解説対象範囲

第2章 mruby のバイトコードとVirtual Machine
2.1 mruby のバイトコードのバイナリ構造
2.2 mruby のVirtual Machine(VM) 
2.3 mruby のOperation code

第3章 mrubyの実装
3.1 ソースコード構造
3.2 バイトコード変換の実装
3.3 VMの実装
3.4 パフォーマンスについて

第4章 mrbgem拡張
4.1 mrbgemとは
4.2 mrbgemの作り方
4.3 mrbgemのAPI

第5章 mruby Operation Code リファレンス
5.1 OP_NOP
・・・全OpCode・・・
5.94 OP_STOP

さいごに
　謝辞
　応用例（PicoRubyの紹介）
　著者紹介
```

## 著者プロフィール

kishima
- X: [@kishima](https://x.com/kishima)
- github: [kishima](https://github.com/kishima)


# 過去に執筆した文章や書籍など

- mrubyに関する同人誌 ３冊
    - https://silentworlds.info/my-books/
- mrubyに関する内容でRuby Kaigi 2020 Takeout採択
    - https://rubykaigi.org/2020-takeout/speakers/