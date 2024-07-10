# PTT: Programming Tools and Techniques (Archived)

## 本レポジトリについて

このレポジトリは，1976年から2014年まで続いていたPTT（Programming Tools and Techniques）という私的な研究会（所謂birds of a feather）のWebページのアーカイブです．

[佐藤重幸](https://satoshigeyuki.github.io/)が，PTT休止時点の最後の幹事である荒堀喜貴氏の許諾の下，Webサイトのデータを引き継いで，アーカイブ化しています．

本レポジトリに関する問い合わせは，佐藤重幸 <sato.shigeyuki@uec.ac.jp> 宛にメールを送ってください．
オープンに議論したい場合には，issueを使ってもらっても構いません．

ただし，アーカイブという性質上，pull requestは受け付けておらず，機械的にrejectします．
特別な理由が無い限り，Webページの記載内容を変更しません．

## 現在のWebサイトについて

原則として，元のWebサイトのデータをそのまま `docs/` ディレクトリ以下に置いて，[GitHub Pagesを用いて公開しています](https://ptt-bof.github.io/archive/)．
元サイトにおいてインデックスページから辿れないファイル（例えばWebページ管理者用のファイルに見えるもの）も，画一的に `docs/` に設置しています．

ただし，管理上の都合により，僅かに変更を加えています．主要なものは，次の通りです．

* 明らかに公開を意図されていない `*~` や `.htaccess` の削除．
* 文字コードの UTF-8 (LF) への統一．Cf. [062e3d2](https://github.com/ptt-bof/archive/commit/062e3d23c09bd33a7efaadb1ebf2009f5c9748b5), [faaac38](https://github.com/ptt-bof/archive/commit/faaac38a61f11cb99ebf1bd6148fb7cc534d56b5).
* HTMLファイルのリネーム．Cf. [0896e46](https://github.com/ptt-bof/archive/commit/0896e46b6ba3a4e3d51cef21a70987c0ec9c915d), [ec0276e](https://github.com/ptt-bof/archive/commit/ec0276e35fc92483910443c1049943ee31b3c0cc).
* インデックスページ冒頭への注釈の追加．Cf. [998f37c](https://github.com/ptt-bof/archive/commit/998f37ca09b53d4dea2ec46aba52a07c9d4cd162).

尚，元サイトの生データのスナップショットは，[ptt.tar.gz](https://github.com/ptt-bof/archive/blob/backup/ptt.tar.gz)にあります．

これらの元サイトのデータに加えて，GitHub Pagesでホストするために `docs/.nojekyll` を追加しています．
