# プログラミング用フォント Ricty Diminished

[Ricty Diminished（リクティ・ディミニッシュト）](https://rictyfonts.github.io/diminished) は [Ricty](https://rictyfonts.github.io/) の姉妹フォントであり、 Linux 環境での研究・開発を想定したプログラミング用フォントです。テキストエディタやターミナルエミュレータ、プログラミング言語やマークアップ言語に対する使用に適しています。[Inconsolata](http://levien.com/type/myfonts/inconsolata.html) と [Circle M+ 1m](http://mix-mplus-ipa.osdn.jp/) の合成、および、プログラミング用フォントとしてのいくつかのチューニングを行ったフリーな TrueType フォントを配布しています。JIS 第二水準の漢字が不足しているため Ricty Diminished と命名しました。

また、JIS 第四水準の漢字をサポートする姉妹フォント [Ricty](https://rictyfonts.github.io/) は生成スクリプトを配布しています。

# 特徴

* ラテン文字には [Inconsolata](http://levien.com/type/myfonts/inconsolata.html) が適用されます。
* それ以外の文字には [Circle M+ 1m](http://mix-mplus-ipa.osdn.jp/) が適用されます。[M+ M Type-1](http://mplus-fonts.osdn.jp/) の美しいグリフと Circle M+ 1m の判読性の高い和文文字（半濁音など）が使用できます。
* 半角文字と全角文字の横幅の比が 1:2 に調整されています。
* 全角スペースが可視化されます。
* いくつかの全角グリフが対応する半角グリフと差別化されています。
* en ダッシュ、em ダッシュが破断線のようになります (LaTeX での入力ミス防止のため)。

# 派生フォント Ricty Diminished Discord

[Ricty](https://rictyfonts.github.io/) と同様に、Ricty Diminished にも Discord（不協和音）版が存在します。Ricty Diminished Discord は、判読性向上のため、調和・統一感を犠牲にして、プログラミング用フォントのコアである Inconsolata 由来の ASCII 文字に手を入れた Ricty Diminished の派生フォントです。

# ライセンス

* Ricty Diminished および Ricty Diminished Discord は [SIL Open Font License (OFL) Version 1.1](http://scripts.sil.org/ofl) に従うものとします。

# バージョン

## (unofficial) Version 4.1.1.20200415 (15 Apr 2020)

* Ricty generate script 4.1.1 modified by itouhiro
    * Remove Hinting.  ヒンティング情報を除去
* Inconsolata 2.001
* Circle M+ 1m 1.063a

## Version 4.1.1 (3 Dec 2017)

* Ricty 生成スクリプト 4.1.1
    * 斜体生成スクリプトの Ricty 生成スクリプトへの統合
* Inconsolata 2.000
* Circle M+ 1m 1.060

## Version 4.1.0 (30 Dec 2016)

* Ricty 生成スクリプト 4.1.0
    * Ricty Discord 生成スクリプトの Ricty 生成スクリプトへの統合
    * Inconsolata 2.000 対応
* Inconsolata 2.000
* Circle M+ 1m 1.060

## Version 4.0.1 (28 Jan 2016)

* Ricty 生成スクリプト 4.0.1
    * ヒンティング情報の付与
* Inconsolata 1.016
* Circle M+ 1m 1.060

## Version 4.0.0 (31 Dec 2015)

* Ricty 生成スクリプト 4.0.0
    * Inconsolata.otf から Inconsolata-Regular/Bold.ttf への切り替え
    * Inconsolata をボールド化するオプションの廃止
* Inconsolata 1.016
* Circle M+ 1m 1.060

## Version 3.2.4 (7 Dec 2014)

* Ricty 生成スクリプト 3.2.4
    * ライセンス変更（public domain → 二条項 BSD）
* Inconsolata 001.010
* Circle M+ 1m 1.056

## Version 3.2.3 (4 May 2014)

* Ricty 生成スクリプト Version 3.2.3
    * ASCII グリフのボールド体の太さの変更（以前の太さにするときは -b）
* Inconsolata Version 001.010
* Circle M+ 1m Version 1.056

## Version 3.2.2 (9 June 2013)

* Ricty 生成スクリプト Version 3.2.2
    * 全角括弧を半角括弧と差別化
* Inconsolata Version 001.010
* Circle M+ 1m Version 1.055

## Version 3.2.1 (6 Nov. 2012)

* Ricty 生成スクリプト Version 3.2.1
    * M+ FONTS LICENSE 記述の除去（Migu 1M の更新に追従）
    * いくつかの環境で等幅でなくなる問題に対処
    * em ダッシュ処理の修正
* Inconsolata Version 001.010
* Circle M+ 1m Version 1.052
