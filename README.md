# README

FreeCodeCamp の Machine Learning with Python Projects の３つめの課題 [Book Recommendation Engine using KNN](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/book-recommendation-engine-using-knn) です．

## 要件まとめ

* データの可視化
  * この要件はオプションで，必須ではない
  * 可視化すると，ほとんどの本は全然評価をつけられていないことがわかる

* データのクリーニング
  * データセットから 200 未満の評価しかつけていないユーザを取り除く
  * 100 個未満の評価しかつけられていない本も取り除く

* `get_recommends` という名前の関数を実装する
  * 本のタイトルを引数に受け取り，似ている本のタイトルと，その距離の組を5冊分返す関数
  * `sklearn.neighbors` から `NearestNeighbors` を利用するとよい