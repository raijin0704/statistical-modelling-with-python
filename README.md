# statistical-modelling-with-python

## 概要

久保先生の「データ解析のための統計モデリング入門」をPythonで実装していきます．

「各チャプターまとめ」 + 「実装方法まとめ」です．

## 各チャプターまとめ

### 目次

* [1章 データを理解するために統計モデルを作る](各チャプターまとめ/chapter01.ipynb)
* [2章 確率分布と統計モデルの最尤推定](各チャプターまとめ/chapter02.ipynb)
* [3章 一般化線形モデル (GLM)](各チャプターまとめ/chapter03.ipynb)
* [4章 GLMモデルの選択 –AICと当てはまりの良さ–](各チャプターまとめ/chapter04.ipynb)
* [5章 GLMの尤度比検定と検定の非対称性](各チャプターまとめ/chapter05.ipynb)
* [6章 GLMの応用範囲を広げる](各チャプターまとめ/chapter06.ipynb)
* [7章 一般化線形混合モデル (GLMM)](各チャプターまとめ/chapter07.ipynb) (※ Rで実装しています!)


### 留意点

* 著作権の問題を考慮し，本文内容には必要最小限にしか触れません．
* 同様の理由で，教科書のRコードもなるべく写さないようにしています．
  * 代わりに，Jupyter Notebookの1ブロックは教科書のコードブロックとほぼ完全に対応しています．教科書があれば容易に比較できるはずです．
* Iris等のサンプルデータはすべて.gitignoreしてあります．
* 変数の命名規則は，たとえPythonicではない場合でも，教科書に合わせてあります．
  * 変数名のピリオド (.) はアンダースコア (_) と置換しています．
* 「教科書に記載されたRの出力と等しい」という意味で，チャプターまとめはほぼ間違いなく正しく実装されています．
  * 出力が正しいだけで，実装も正しいとは言い切れません．間違いがあればご指摘いただけると助かります．
* 以下は2017年現在，Pythonに対応する機能がありません．
  * stepAIC: Rを呼ぶほどでもないので，今回は関数を自作しました ([関連記事](http://mytk0u0.net/step-aic-with-python.html#step-aic-with-python))
  * GLMM: Rで実装しました．

## 実装方法まとめについて

「結局どういうコード組めばいいの」のためのまとめ…になる予定．
