# 計算量
## 時間計算量
コンピュータが与えられた問題を解く際に必要とする手順の回数。

少ないほどより短い時間で解を求められる。

## 空間計算量
コンピュータが与えられた問題を解く際に必要とする記憶領域の容量。

少ないほどより少ないメモリ容量で解を求められる。

## オーダー記法
値の変化を大まかに評価するための記法。計算量の評価に用いる。

```f(x) = O(x^2)```

有名なオーダーには名前がつけられているものもあり、以下に記す

- 「定数時間」  ```O(1)```
- 「対数時間」  ```O(log n)```
- 「線形時間」  ```O(n)```
- 「準線形時間」|「線形対数時間」 ```O(n log n)```
- 「二乗時間」  ```O(n^2)```
- 「多項式時間」```O(n^c）```（cは1以上の定数）
- 「指数時間」  ```O(k^n)```
- 「階乗時間」  ```O(n!)```

### kwsk
- O(1)
  - データ量にかかわらずステップ数1固定。
- O(n)
  - nが2倍、3倍と増えると計算量も同様に2倍、3倍となる。
- O(log n)
  - 計算量と求める場合は底を2として考える。nが2倍、3倍と増えても計算量は1、2と増える程度であるため有用である
- O(n log n)
  - O(log n)にnの計算量がかけられたもの。nが2倍になると計算量は2.5倍。nが10倍になると計算量は20倍。nが100倍になると約300倍になる。
- O(n^2)
  - n個の要素を用いた総当たりの組み合わせを求めるパターン。特に計算量が多い。

![complexify](https://www.techscore.com/blog/wp/wp-content/uploads/2016/08/76c691c22c7ef40a64aa64b04f05e90c-768x475.png)
> https://www.techscore.com/blog/wp/wp-content/uploads/2016/08/76c691c22c7ef40a64aa64b04f05e90c-768x475.png
## まとめ
時間計算量も空間計算量も少ないアルゴリズムは優れたものであるといえる。

一般的には問題というのは、メモリを多く増やせば短時間で解け、また少ないメモリで長時間かけて解けるため

**「時間と空間のトレードオフ」** の関係が現れることが多い

# 記法
## Big - O Notation (O)
## Omega Notation (Ω)
## Theta Notation (θ)

# データ構造
## Array, String
## Linked list
## Stack
## Queue
## Tree
## Heep
## Disjoint set ADT
## Graph

# Algorithms
## sorting
## searching
## selection 
## symbol tables
## hasing
## dynamic programing
## divibe and conquer
## greedy algorithm

# 勉強できるサイト
- [Geeks for geeks](https://www.geeksforgeeks.org/)
- Tutorials point
- Javatpoint
- Programiz
- Freeecodecamp
- Codestudio