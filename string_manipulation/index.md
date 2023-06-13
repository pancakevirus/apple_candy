# 文字列操作

この章では Ring の学習を諦めてしまう
原因のひとつである文字列処理について
詳しく解説していきます。

マニュアルに記載されていない誰にも気付いてもらえない
サンプルソースがあるだけなので、ここで必ず挫折してしまうのはわかります。
加えてQtや英文読解に関する知識や経験も必要なので、やはり初学者は挫折してしまうかと。

もったいないですね。

## 事前知識

Ring 本体だけでは英語以外では扱えません。
ほかのプログラミング言語にあるような多言語処理に対応した機能が欠落しています。
そして、今後もこのような機能を実装することはないでしょう。

ではどうするかと言うと、公式には Qt 拡張機能を使うことになります。

## 目次 (文字列処理)

* RingQt
 * 文字列の長さを得るには
 * 挿入
 * 削除
 * 反復
 * 表示
 * 検索
 * 抽出
 * 分割
 * 連結
 * 正規表現
 * 全角・半角の変換
 * ひらがな・カタカナの変換
 * ローマ数字・漢数字の変換
 * 西暦・和暦の変換
 * 文字コードの変換
 * 文字コードの判定
 * Base64 のエンコードとデコード
 * JSON の解析処理
 * XML の解析
 * エスケープ処理
 * エスケープシーケンス
 * 作例: 連番作成ツール
 * 続く...