# バギング
 bootstrap+aggregating
 ブートストラップ
 復元抽出
 元データが100個ならブートストラップサンプルも100個にすることが多い
 100個のサンプル集合が何個もある
 それぞれの集合で学習する⇨弱学習機⇨多数決or平均など
 
 # ブースティング
 弱学習機を順番に学習して組み合わせて強くしていく
 前の学習機が誤ったデータに関して次の段で重みを強くする．
 
 # 弱学習器の種類
 決定木
 
 # AdaBoost
 学習器の重み：精度から決める．その学習器からの結果をどれだけ信用するか
 