Sphinx朝会やるよ!!
===================


Sphinx朝会って?
----------------------
Sphinx朝会とは

* **Sphinx初心者向け** の
* 'make html'を体験するための
* 勉強会みたいなもの

です。

今回で3回目。
----------------------

今回で3回目の実施です。

* 第一回:兵庫・神戸
* 第二回:大阪・十三
* **第三回:兵庫・神戸** ←イマココ


いつやるの?(開催情報)
----------------------

   :日時: 2012/03/04 10:00 to 12:00
   :会場: 神戸市立婦人会館 4階 たんぽぽ
   :URL: http://atnd.org/events/25549
   :Hashtag: #sphinxjp

何をやるの?
----------------------

基本的に前回二回と内容は同じです。

* Sphinxの環境を作る
* はじめての'make html'
* 演習問題で学習する

Sphinxについて
----------------------

.. s6:: styles

    h2: {fontSize:'100%', textAlign:'center', margin:'30% auto'}

Sphinxとは何か？
-----------------
* ドキュメント生成のツール
* reStructuredText記法(Wikiっぽい?
* ページ間のリンクを自動生成
* 強力なコードハイライト
* HTML, PDF, ePub, htmlhelp, latex, man...


reStructuredText記法って?
-------------------------

シンプルなテキストマークアップです。

.. code-block:: rst

   Sphinxとは何か？
   -----------------
   * ドキュメント生成のツール
   * reStructuredText記法(Wikiっぽい?
   * ページ間のリンクを自動生成
   * 強力なコードハイライト
   * HTML, PDF, ePub, htmlhelp, latex, man...

何が嬉しい?
--------------------------
Sphinxでドキュメントを書くと…

* テキストエディタでサクサク書ける
* 文書の構造を保ってシンプルに書ける
* 強力なSphinx拡張も使える
* 様々なOSで動作

.. s6:: styles

    'ul/li': {display:'none'}

.. s6:: actions

    ['ul/li[0]', 'fade in', '0.3'],
    ['ul/li[1]', 'fade in', '0.3'],
    ['ul/li[2]', 'fade in', '0.3'],
    ['ul/li[3]', 'fade in', '0.3'],


テキストエディタでサクサク
--------------------------
何せテキストなので、

* GitなどのVCSで管理可能
* コピペし放題（?）
* テキストエディタ上の見栄えが崩れにくいマークアップ

シンプルに書ける
--------------------------
* マークアップはシンプル。
* インデントと改行が文書構造を表現


強力なSphinx拡張
------------------------
reSTructuredTextでなく、 **Sphinx** である必要。

* コードハイライト(pygments)
* 拡張テーマ(bizstyle,S6,etc...)
* blockdiag等


Sphinxインストール方法
-----------------------

Pythonがインストールされている環境で

.. code-block:: bash

   $ easy_install sphinx

あとは適当にディレクトリ作って…

.. code-block:: bash

   $ sphinx-quickstart

'make html'
-------------------
HTMLを作成するのに'make html'ってやります。

   :html: HTMLを作成します
   :epub: EPUBを作成します
   :pdf: PDFを作成します(要追加設定)

情報も充実のSphinx-Usres.jp。
------------------------------
日本のコミュニティが活発。

* ユーザーグループのページ
   * http://sphinx-users.jp/
* メーリングリスト
   * http://www.python.jp/mailman/listinfo/sphinx-users

Twitterでも
-----------

#sphinxjp ハッシュタグを付けてつぶやいてみてください。


その気になれば議事録的なものも
------------------------------

* http://dl.dropbox.com/u/3864210/golang_kobe1.html
* http://dl.dropbox.com/u/3864210/Concrete5_4.html
* http://dl.dropbox.com/u/3864210/Concrete5_5.html


Sphinxの人気!!
-----------------

* Blender Python API Document
* CakePHP2.x と Symfony2、PHPフレームワークのドキュメントに採用(CodeIgniterさん…)
* 岡山Javaユーザ会

   * http://sphinx.pocoo.org/examples.html

大事なので2回いいます(開催情報)
-------------------------------

   :日時: 2012/03/04 10:00 to 12:00
   :会場: 神戸市立婦人会館 4階 たんぽぽ
   :URL: http://atnd.org/events/25549
   :Hashtag: #sphinxjp



Thanks for watching!!
----------------------

ホントはBlenderやりたいんだよね…

.. raw:: html

   <div align='center'><iframe width="560" height="315" src="http://www.youtube.com/embed/Z8cUMsQFHp4" frameborder="0" allowfullscreen></iframe></div>
   
