## Graph theory とくに Ramanujan graphs

- Ramanujan graph が定義されたのは A. Lubotzky, R. Phillips & P. Sarnak (1988) の論文 ( https://doi.org/10.1007/BF02126799 )．
- zig-zag product が定義されたのは Omer Reingold, Salil Vadhan, Avi Wigderson (2002) の論文 ( https://doi.org/10.2307/3062153 )． 
- Noga Alon のエルデシュ数は 1 である (エルデシュとの共著論文 https://doi.org/10.1007/BF02187731 )．
- Xiao-Dong Zhang, "The Laplacian eigenvalues of graphs: a survey" ( https://doi.org/10.48550/arXiv.1111.2897 )

Ramanujan graph の例
- 2-正則連結グラフ
- 完全グラフ
- Payley graph (有限体とその上の二次指標から定義されるループのない単純連結グラフ．強正則グラフの例でもある．特殊な場合はCayleyグラフでもある．)

Expander族の構成
- Margulis 1973 (アフィン変換群の表現論?)
- 

Integral Circulant Graphs
- arithmetic features
- Ramanujan property
- energy of graphs

### 確認

- [ ] On the Paley graph of a quadratic character https://doi.org/10.48550/arXiv.2212.02005
- [ ] On the eigenvalues of the graphs D(5,q) https://doi.org/10.48550/arXiv.2207.04629

### 有限距離空間（位相空間）

- マグニチュードホモロジー
  - [講義ノート](http://www.math.titech.ac.jp/~kgomi/slides/mh.pdf) | [LP](http://www.math.titech.ac.jp/~kgomi/talk_j.html)

### 固有値の数値解法

- 一般に行列の固有値を代数的に求める方法は存在しない。代数方程式の解はその同伴行列の固有値であるため、行列の固有値を代数的に求める方法が存在すれば任意の代数方程式の代数的解法が存在することになる。しかしガロア理論によると一般の代数方程式の代数的解法は存在しない。


## 時系列分析

カルマンフィルタが提案されたのは R. E. Kalman の論文 ( https://scholar.google.jp/scholar?cluster=5225957811069312144 )．

- [ ] https://www.kalmanfilter.net
- [ ] 線形カルマンフィルタの基礎 ( https://doi.org/10.11499/sicejl.56.632 )
- [ ] 慶應大学講義 応用確率論
  - [ ] 第13回 ベイズの方法 カルマンフィルタ(1) https://youtu.be/P85JCE3tZWY
  - [ ] 第14回 ベイズの方法 カルマンフィルタ(2) https://youtu.be/g3JIQVavoNk

## Linux (CentOS Stream 9)

### 環境変数の設定

`~/.bash_profile` に `export NAME="value"` の形式で記入する．
変数にはシェル変数と環境変数があり，環境変数を設定するためにはシェル変数を `export` する必要がある．
`~/.bash_profile` は bash がログインシェルとして起動したときに実行される．


## Julia 言語

### Jupyter Notebook (Jupyter Lab) に Julia のカーネルを追加する方法

```Julia
julia> ]
pkg> add IJulia
```

### 既存の Notebook の Julia のバージョンを変更する方法

```
Kernel → Change Kernel
```

## R 言語

### Jupyter Notebook に R のカーネルを追加する方法

```R
> install.packages('IRkernel')
> IRkernel::installspec()
```

## Functional programming

- [ ] [Hughes95] The design of a pretty-printing library ( https://doi.org/10.1007/3-540-59451-5_3 )


## 海賊版の文献にアクセスする方法

! 以下のサイトにアクセスしては**いけない**．

1. Sci-Hub (DOIで検索する) https://sci-hub.se | https://sci-hub.st | https://sci-hub.ru
2. Library Genesis+ (ISBNなどで検索する) https://libgen.li | https://libgen.gs | https://libgen.lc
