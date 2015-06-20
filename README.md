# elinyad-api

（プロジェクトが始動するまでの間の、暫定的なreadme.mdです）

キャラクターデータベース（キャラDB)「エリンヤド」に実装予定の規格形式やAPIを扱うレポジトリです。

具体的には

・キャラDBから選択された任意のアイテムから必要な情報を選別し、規格フォーマット(xml,jsonなど）に従ったテキストデータとして出力・整形するJoomla Plugin。

・上記のテキストデータに、アイテムに関連づけられた画像や音声・動画などのメディアを付加し、一般的な圧縮フォーマット（zipなど）、もしくは独自の圧縮フォーマットで圧縮して単一のファイルにするphpスクリプト。

・キャラDBに登録されたキャラを、スニペット・ガジェットとして簡単にhtmlに貼り付け可能にするAPI。

など、現段階では、小規模なAPIを一括的にこのプロジェクトで管理していく予定です。

実際のコーディングについては、エリンヤドと並行して開発されているアプリ・ゲームでキャラDBへのアクセスが必要になった段階で始まることになります。

キャラDB自体は、アプリ・ゲームの開発者が個人・企業を問わずオープンにアクセスできるデータベースとなります（ただし、データベースへの負荷の状況によっては、アクセスを制限するシステムも必要になるかもしれません）。


＊　このプロジェクトでは、現時点では、キャラDBの規格形式やAPIに関する問題のみ扱います。キャラDBに登録されたキャラの著作権、エリンヤドのサイトに関する問題などはここでは扱いません。



(作者(elin)より - おそらくコーディングなど一人での作業になると思いますが、公開するデータの公平性のためや、キャラDBを利用したいという開発者が他にもおられた場合の参考ドキュメントとして、公開リポジトリとしています。もちろん、プロジェクトへの参加、規格・APIに関する問題の指摘・要望など歓迎です。最後に、githubに不慣れなため、このreadmeも含め何か不作法がありましたらご容赦下さい。ご指摘頂けると助かります)



