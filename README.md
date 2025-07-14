# 2025
ゼミ2025年度

## ナッシュ均衡の計算
* [アルゴリズムのリスト](https://github.com/OyamaZemi/algorithms/tree/master/nash_equilibrium)
* Equilibrium Computation for Two-Player Games in Strategic Form:
  [Part I](https://www.oyama.e.u-tokyo.ac.jp/theory16/vonStengel07_1.pdf),
  [Part II](https://www.oyama.e.u-tokyo.ac.jp/theory16/vonStengel07_2.pdf),
  [Part III](https://www.oyama.e.u-tokyo.ac.jp/theory16/vonStengel07_3.pdf)
* [Vertex Enumeration と Facet Enumeration](HVrep.pdf)

## 自由課題
* [QuantEcon.py](https://github.com/QuantEcon/QuantEcon.py),
  [QuantEcon.jl](https://github.com/QuantEcon/QuantEcon.jl),
  [GameTheory.jl](https://github.com/QuantEcon/GameTheory.jl),
  [ContinuousDPs.jl](https://github.com/QuantEcon/ContinuousDPs.jl)
  などのライブラリのソースファイルを ChatGPT に読み込ませてバグがないか聞いてみる．
  バグが発見されたら，修正してプルリクエストを出す．
* QuantEcon.py の [`Kalman`](https://github.com/QuantEcon/QuantEcon.py/blob/main/quantecon/_kalman.py) 用のテストを加える．
  - [test_kalman.py](https://github.com/QuantEcon/QuantEcon.py/blob/main/quantecon/tests/test_kalman.py)
  - [#128](https://github.com/QuantEcon/QuantEcon.py/issues/128)
  - [Coverage](https://coveralls.io/builds/74588189/source?filename=quantecon%2F_kalman.py)
* QuantEcon.py の `LinearStateSpace` 関連のイシュー
  ([#354](https://github.com/QuantEcon/QuantEcon.py/issues/354), [#374](https://github.com/QuantEcon/QuantEcon.py/issues/374))
  の解決を考える．
* QuantEcon.py の [howson_lcp.py](https://github.com/QuantEcon/QuantEcon.py/blob/main/quantecon/game_theory/howson_lcp.py) を改善する．
  - [Howson 論文](https://www.jstor.org/stable/2634798)を読んでみる．
  - Numba を使って高速化できる箇所を探す．
* QuantEcon.py の [lemke_howson.py](https://github.com/QuantEcon/QuantEcon.py/blob/main/quantecon/game_theory/lemke_howson.py) を Julia に翻訳する．
* [ContinuousDPs.jl](https://github.com/QuantEcon/ContinuousDPs.jl) に
  multidimensional-state stochastic growth model のテストケースを書く．
  - Santos (1999)
    "[Numerical solution of dynamic economic models](https://www.sciencedirect.com/science/article/abs/pii/S1574004899010083),"
    Handbook of Macroeconomics, Chapter 5 の7.3節のモデルが候補
*
