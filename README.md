# Python_program_report
大学のレポート課題で作成したプログラム（Python）を、プログラミング演習、卒業研究、修士研究を通して身につけたプログラミング力で再編集したものを公開します。
現在は、研究室でMATLABが使用されていることや、学部時代の実習の影響で、MATLABの使用がメインです。
大学院の深層学習の講義の演習やレポート課題でPytorchやTensorflowを使うことがあって、久しぶりにPythonに触りました。

## 公開しているプログラムに関する注意事項
- レポート課題のため、先生から一部ライブラリの使用が禁止されていることもあり、「〜〜ライブラリの〜〜関数を使えば、数行で実装できるのに...」と思える部分も何行も使って実装しています。
- レポート課題でのルール（どのライブラリは使用可/使用不可）は公開しません。基本的にソースコードの初めに「import ~~ as ##」と書いてインポートしているものは、課題提出時の際に使用してよいライブラリと先生から指定されたものです。
- ここで公開しているプログラムは下記のどれかにあたります。
  - 実際の問題と類似する参考書の問題の実装（実際のレポート課題をそのまま公開することはできないため、代わりに参考書の問題を実装した結果をアップロードしています）
  - 適当なオープンデータを見つけて解析する課題で使用したプログラムを再編集したもの。
  - よく使われているデータセットを使用して解析する課題で使用したプログラムを再編集したもの。
- 先生が作成されたサンプルコードを改変して提出するだけの課題で使用したPythonファイルは公開していません。本Githubにアップロードしているものは、全て自分がゼロから作成したもので、課題提出時のルールを満たしているものです。

（最終更新：2021/9/24）

## 1：backtrack
過去に「バックトラック直線探索を用いた勾配法」を実装する課題がレポート課題に出されました。
本Githubには実際の問題ではなく、参考書にのっている問題を解くために使用したプログラムとその説明をまとめたPDFファイルをアップロードしています。

この課題に関連する話として、レポートを作成した当時のプログラミング能力が低すぎることを嘆いているnote記事はこちらです。
https://note.com/anmitsu48/n/n4a498bf36a5c

（最終更新：2021/9/24）

## 今後アップロード予定のプログラム
- Lagrange乗数法、双対法に基づく制約付き最適化問題
- Iris Data Set に対する主成分分析、k-meansクラスタリングの実行
- シンプルなオートエンコーダによる画像ノイズ除去（PyTorch）

※ 過去の課題を振り返ると、MATLABの使用が多かったことと、先生が作成されたサンプルコードを改変して提出する課題が多かったです。
そのため、Pythonファイルで公開予定のものは上記の3つのみです。（この3つは全部自分がゼロから作成したものである）
将来、「Pythonでも実装してみた」シリーズとして、MATLABで実装して提出したプログラムのPython版を公開する可能性もあります。

（最終更新：2021/9/24）
