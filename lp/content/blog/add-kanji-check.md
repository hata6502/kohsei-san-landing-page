---
title: 漢字チェック機能でわかりやすい文章作成をサポート
date: 2020-12-08T00:00:00+09:00
# post image
image: /lp/images/blog/495597_m.jpg
# post type (regular/featured)
type: featured
# meta description
description:
  校正さんに漢字チェック機能を追加しました。
  文章中で使われている漢字が常用漢字または人名用漢字であることをチェックします。
  日常的に使われている漢字のみを使うことで、文章がよりわかりやすくなります。
# post draft
draft: false
---

[校正さん](https://kohsei-san.b-hood.site/lp/)に漢字チェック機能を追加しました。
文章中で使われている漢字が常用漢字または人名用漢字であることをチェックします。
日常的に使われている漢字のみを使うことで、文章がよりわかりやすくなります。

<br>
<hr>
<br>

### 常用漢字と人名用漢字
<br>

#### 常用漢字は「一般の社会生活で使われる漢字」

[常用漢字](https://ja.wikipedia.org/wiki/%E5%B8%B8%E7%94%A8%E6%BC%A2%E5%AD%97)は**一般の社会生活で使われる漢字**です。
たとえば「健康」、「元気」などが含まれます。
しかし「溌剌（はつらつ）」といった漢字は含まれません。
<br>

#### 人名用漢字は「戸籍に記載できる漢字」

[人名用漢字](https://ja.wikipedia.org/wiki/%E4%BA%BA%E5%90%8D%E7%94%A8%E6%BC%A2%E5%AD%97)は**戸籍に子の名として記載できる漢字のうち、常用漢字を除いたもの**です。
たとえば「伊藤」、「秦」などが含まれます。
常用漢字と人名用漢字を組み合わせることで、日常的に使われている漢字を網羅できるといえるでしょう。

<br>
<hr>
<br>

### 漢字をチェックする textlint プラグインも公開

校正さんは [textlint](https://github.com/textlint/textlint) と呼ばれる文章校正エンジンを利用しています。
校正さんの漢字チェック機能公開にあわせて、漢字をチェックする textlint プラグインも[オープンソース](https://ja.wikipedia.org/wiki/%E3%82%AA%E3%83%BC%E3%83%97%E3%83%B3%E3%82%BD%E3%83%BC%E3%82%B9)として公開しました。

- [textlint-rule-ja-joyo-or-jinmeiyo-kanji](https://github.com/hata6502/textlint-rule-ja-joyo-or-jinmeiyo-kanji) 常用漢字または人名用漢字であることをチェックするtextlintルール
- [textlint-rule-ja-kyoiku-kanji](https://github.com/hata6502/textlint-rule-ja-kyoiku-kanji) 教育漢字であることをチェックするtextlintルール
