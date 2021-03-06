# PyCaret-Learn
 PyCaret(1.0)の勉強の記録です。

# Requirement
 
* PyCaret 1.0.0

# Installation
 
Jupyter Notebookでipynbファイルを開いてください。

# Contents

* <b>01.Binary-Classification-Sample</b>

　　クラス分類のサンプルです。<br>
　　PyCaretのチュートリアルのほぼ写経＋日本語コメントです。
  
　　<!-- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kazuhito00/PyCaret-Learn/master?filepath=01.Binary-Classification-Sample/01.Binary-Classification-Sample.ipynb)<br>　　※compare_models()やtune_model()の実行時間が少々長いため注意 -->
  
* <b>02.Regression-Sample</b>

　　回帰分析のサンプルです。<br>
　　PyCaretのチュートリアルのほぼ写経＋日本語コメントです。

　　<!-- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kazuhito00/PyCaret-Learn/master?filepath=02.Regression-Sample/02.Regression-Sample.ipynb)<br>　　※compare_models()やtune_model()の実行時間が少々長いため注意 -->

* <b>03.Clustering-Sample</b>

　　クラスタリングのサンプルです。<br>
　　PyCaretのチュートリアルのほぼ写経＋日本語コメントです。

　　<!-- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kazuhito00/PyCaret-Learn/master?filepath=03.Clustering-Sample/03.Clustering-Sample.ipynb) -->
  
* <b>04.Anomaly-Detection-Sample</b>

　　異常検知(教師無し学習)のサンプルです。<br>
　　PyCaretのチュートリアルのほぼ写経＋日本語コメントです。

　　<!-- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kazuhito00/PyCaret-Learn/master?filepath=04.Anomaly-Detection-Sample/04.Anomaly-Detection-Sample.ipynb) -->
  
* <b>05.Natural-Language-Processing-Sample</b>

　　自然言語処理のサンプルです。<br>
　　PyCaretのチュートリアルのほぼ写経＋日本語コメントです。<br>
　　※言語モデルのダウンロードと設置が必須のためBinderのリンクは用意していません
 
　　<!-- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kazuhito00/PyCaret-Learn/master?filepath=05.Natural-Language-Processing-Sample/05.Natural-Language-Processing-Sample.ipynb)<br>　　※compare_models()やtune_model()の実行時間が少々長いため注意 -->
  
* <b>06.Association-Rule-Mining-Sample</b>

　　相関ルールマイニングのサンプルです。<br>
　　PyCaretのチュートリアルのほぼ写経＋日本語コメントです
 
　　<!-- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kazuhito00/PyCaret-Learn/master?filepath=06.Association-Rule-Mining-Sample/06.Association-Rule-Mining-Sample.ipynb) -->

# Extra Contents

 
* <b>10.Binary-Classification-Titanic-Sample</b>

　　KaggleのTitanicのサンプルです（Public Leaderboard Score：0.79904）

　　また、本サンプルはKaggle上のNotebookとしても用意しています。<br>
　　https://www.kaggle.com/kazuhito00/pycaret-binary-classification-titanic-sample

　　<!-- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kazuhito00/PyCaret-Learn/master?filepath=10.Binary-Classification-Titanic-Sample/10.Binary-Classification-Titanic-Sample.ipynb)<br>　　※compare_models()やtune_model()の実行時間が少々長いため注意 -->

* <b>11.Regression-Ion-Switching-Competition</b>

　　Kaggleの[University of Liverpool - Ion Switching](https://www.kaggle.com/c/liverpool-ion-switching) のサンプルです（Public Leaderboard Score：0.937）
  
　　コンペのデータの他に、以下のドリフトデータ除去済みのデータを利用しています。<br>
　　<https://www.kaggle.com/cdeotte/data-without-drift>
  
　　<!-- [![Binder](https://mybinder.org/badge_logo.svg)]() -->
  
# Note0 
現行Ver(1.0.0)を使う時に意識しておきたいこと
* [【ボタ山話#10】PyCaret解説と機械学習自動化系ツールとの向き合い方](https://shirokane-kougyou.fm/episode/25)

# Note1
参考にしたい記事
* [PyCaretでできる前処理について調べてみた](https://qiita.com/tomiyou/items/e1842775e7aaee04ada3)

* [Pycaretの回帰・分類で出力されるグラフの種類について解説](https://qiita.com/ground0state/items/57e565b23770e5a323e9)
  
# Note2
PyCaretとは直接関係ないですが、参考にしたい記事
* [【随時更新】Kaggleテーブルデータコンペできっと役立つTipsまとめ](https://naotaka1128.hatenadiary.jp/entry/kaggle-compe-tips)
<!-- https://trueman-developer.blogspot.com/2019/07/keras.html -->

* [pythonではじめるデータ分析 (データ前処理〜機械学習)](https://qiita.com/CEML/items/b7dc768d1df66e809e5a)

* [機械学習モデルの説明性・解釈性について -SHAPによる実践あり-](https://cpp-learning.com/interpretable-model/)

* [特徴量エンジニアリング備忘録](https://qiita.com/risako_/items/91ea7f34433bfa2ea40c)

* [PythonとAutoMLメモ](https://qiita.com/calderarie/items/6188ce60c3e3dc2c6ba0)/[featuretoolsメモ](https://qiita.com/Hyperion13fleet/items/4eaca365f28049fe11c7)/[tsfreshメモ](https://qiita.com/KI1208/items/e27f827bac8654c9adcc)

* [主成分分析（PCA）の累積寄与率で見る特徴量エンジニアリング](https://www.takapy.work/entry/2019/02/08/002738)

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
PyCaret-Learn-learn is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

# Reference
PyCaret：https://pycaret.org/
