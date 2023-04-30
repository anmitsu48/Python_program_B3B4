# Python_program_report
大学のレポート課題で作成したプログラム（Pythonで作成）を、プログラミング演習、卒業研究、修士研究を通して身につけたプログラミング力で再編集したものを公開します。
現在は、研究室でMATLABが使用されていることや、学部時代の実習の影響で、MATLABの使用がメインです。
大学院の深層学習の講義の演習やレポート課題でのPytorchやTensorflowの使用、インターンシップの実習でのプログラミングでの使用で、久しぶりにPythonに触りました。

## 公開しているプログラムに関する注意事項
- レポート課題のため、先生から一部ライブラリの使用が禁止されていることもあり、「〜〜ライブラリの〜〜関数を使えば、数行で実装できるのに...」と思える部分も何行も使って実装していることがあります。
- レポート課題でのルール（どのライブラリは使用可/使用不可など）は公開しません。基本的にソースコードの初めに「import ~~ as ##」と書いてインポートしているものは、使用が禁止されていないものです。
- ここで公開しているプログラムは下記のどれかにあたります。
  - 実際の問題と類似する参考書の問題の実装（実際のレポート課題をそのまま公開することはできないため、代わりに参考書の問題を実装した結果をアップロードしています）
  - 適当なオープンデータを見つけて解析する課題で使用したプログラムを再編集したもの。
  - よく使われているデータセットを使用して解析する課題で使用したプログラムを再編集したもの。
- 先生が作成されたサンプルコードを改変して提出するだけの課題もありましたが、その課題で提出したPythonファイルは本Githubでは公開していません。本Githubにアップロードしているものは、全て自分がゼロから作成したもので、課題提出時のルールを満たしているものです。

（最終更新：2022/2/10）

## 1：backtrack
過去に「バックトラック直線探索を用いた勾配法」を実装する課題がレポート課題で出されました。
本Githubには実際の問題ではなく、参考書にのっている問題を解くために使用したプログラムとその説明をまとめたPDFファイルをアップロードしています。

この課題に関連する話として、レポートを作成した当時のプログラミング能力が低すぎることを嘆いているnote記事はこちらです。
https://note.com/anmitsu48/n/n4a498bf36a5c

（最終更新：2021/9/24）

## 2：dual
過去に「双対上昇法」を実装する課題がレポート課題で出されました。

この内容に関連するnote記事：https://note.com/anmitsu48/n/ne47459afc550

（最終更新：2022/2/12）


## 今後アップロード予定のプログラム
- 拡張Lagrange乗数法基づく制約付き最適化問題
- Iris Data Set に対する主成分分析、k-meansクラスタリングの実行
- シンプルなオートエンコーダによる画像ノイズ除去（PyTorch）

※ 過去の課題を振り返ると、MATLABの使用が多かったことと、先生が作成されたサンプルコードを改変して提出する課題が多かったです。
そのため、Pythonファイルで公開予定のものは上記に記したもののみです。（これらは全部自分がゼロから作成したものである）
将来、「Pythonでも実装してみた」シリーズとして、MATLABで実装して提出したプログラムのPython版を公開する可能性もあります。

（最終更新：2022/2/10）
