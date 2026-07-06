
#### 逆格子ベクトルを導出

$\bm{K}_1$ は，ナノチューブの円周方向のベクトル $\bm{C}_h$ に対応する逆格子ベクトルである．$|\bm{C}_h| = \pi d_t$

$$
\begin{aligned}
\left\{
\begin{aligned}
\bm{C}_h
&= n\bm{a}_1 + m\bm{a}_2, \\
\bm{T}
&= t_1\bm{a}_1 + t_2\bm{a}_2
\end{aligned}
\right.
\qquad
\left\{
\begin{aligned}
\bm{K}_1
&= \alpha \bm{b}_1 + \beta \bm{b}_2, \\
\bm{K}_2
&= \gamma \bm{b}_1 + \delta \bm{b}_2
\end{aligned}
\right.
\qquad
\begin{aligned}
\bm{a}_i \cdot \bm{b}_j
&=
\begin{cases}
2\pi, & i = j, \\
0, & i \ne j .
\end{cases}
\end{aligned}
\end{aligned}
$$
$(n, m)$はカイラル指数，$(t_1,t_2)$は並進ベクトル係数

$$
\bm{C}_h \cdot \bm{K}_1 = 2\pi \quad \rightarrow 
\quad (n\bm{a}_1 +m\bm{a}_2)(\alpha \bm{b}_1 + \beta \bm{b}_2 )= 2\pi
$$
$$
n(2\pi)\alpha + m(2\pi)\beta = 2\pi \\
n\alpha + m\beta = 1 \quad t_1\alpha + t_2\beta = 0
$$

$$
t_1 \alpha = -t_2 \beta
\quad\Longrightarrow\quad
\alpha = -\frac{t_2}{N},
\qquad
\beta = \frac{t_1}{N},
\qquad
N = m t_1 - n t_2
$$

$$
\frac{-nt_2+mt_1}{N}=1 \quad \rightarrow \quad \alpha = -\frac{t_2}{N} , \beta =\frac{t_1}{N}
$$
以上のことで，逆格子ベクトル$\bm{K}_1$導出しました．
---

#### 円周の長さとの関係

ナノチューブの円周の長さは$|\bm{C}_h| = \pi d_t$．ここで，$d_t$ はナノチューブの直径である．

$\bm{K}_1$ は $\bm{C}_h$ に対応する逆格子ベクトルなので，

$$
\bm{C}_h \cdot \bm{K}_1 = |\bm{C}_h||\bm{K}_1| = 2\pi
$$

と書ける．

したがって，

$$
|\bm{K}_1|
=
\frac{2\pi}{|\bm{C}_h|}
=
\frac{2\pi}{\pi d_t}
=
\frac{2}{d_t}
$$
$$
|\bm{K}_2| = \frac{2\pi}{|\bm{T}|} = \frac{2\pi}{T}
$$
$\bm{K}_1$は円周方向の量子化された波数間隔．
$\bm{K}_1$は軸方向１次元ブリルアン領域の周期である．

---

線分 $WW'$はナノチューブの1次元ブリルアン領域である．

軸方向の実空間周期が $T$ なので，逆空間では周期が $2\pi/T$ になります．  
そのため，その半分ずつを取ると，1次元ブリルアン領域は
$$
-\frac{\pi}{T} < k < \frac{\pi}{T}
$$
ナノチューブでは，円周方向は閉じています．  
したがって，円周方向の波数は連続ではなく，飛び飛びの値になります．
その飛び飛びの値を指定する整数が $\mu$ です．本文では，
$$
\mu = 0,\cdots,N-1
$$
円周方向には $N$ 個の許された波数があり，それぞれに対応して1本の線分ができます．
線分は$WW' + \mu\bm{K}_1$

波数をグラフェンの $E(\bm{k})$ に代入してみる．グラフェンのエネルギーバンドは，2次元波数 $\bm{k}$ の関数として
$$
E(\bm{k})
$$
$$
E_\mu(k)
=
E_{2g}\left(
k\frac{\bm{K}_2}{|\bm{K}_2|}
+
\mu\bm{K}_1
\right)
$$

---

$$
\begin{aligned}
    E_\mu(k) &= E_{2g}\!\left(k \frac{\bm{K}_2}{|\bm{K}_2|} + \mu \bm{K}_1\right), \\
    &\quad \left(\mu = 0, \cdots, N-1,\ -\frac{\pi}{T} < k < \frac{\pi}{T}\right)
  \end{aligned}
$$
$k\frac{\bm{K}_2}{|\bm{K}_2|}$は，**チューブ軸方向に進む波数成分**を表します．
$\frac{\bm{K}_2}{|\bm{K}_2|}$は $\bm{K}_2$ 方向の単位ベクトルです．  
したがって，これに $k$ をかけることで，軸方向の波数ベクトルになります．

$E_{2g}$はグラフェンのエネルギー分散関係を表す．

$\mu$ は，円周方向の量子化番号です．

- $\mu=0$：最初の量子化線
- $\mu=1$：$\bm{K}_1$ だけずれた量子化線
- $\mu=2$：$2\bm{K}_1$ だけずれた量子化線
- $\cdots$
- $\mu=N-1$：最後の独立な量子化線

---

### ナノチューブの状態密度とファンホーブ特異性

状態密度 $D(E)$ ：エネルギーバンド中の単位エネルギーあたりの状態の数

フェルミエネルギー：


<div align="center">

**電子を低いエネルギーの状態から順番に詰めていったとき，電子が占有する一番上のエネルギー**

</div>

$E / |t| = 0$はエネルギーを $|t|$ で割って無次元量である．ここで $t$ は，炭素原子間の $\pi$ 電子のホッピング積分

- 金属チューブ $(9,0)$

金属ナノチューブでは，フェルミエネルギーで状態密度が有限 $D(E) \ne 0$，フェルミエネルギーに電子が存在できる．グラフに$(9,0)$ ナノチューブでは $E/|t|=0$ で状態密度が 0．

- 半導体チューブ

$D(E) = 0$，フェルミエネルギーに電子が存在できない．

---

**ファンホーブ特異性**

ナノチューブの状態密度の鋭いピークは，ファンホーブ特異性という．ネルギーバンド $E(k)$ が，ある $k$ の点で平らになる
$$
\frac{\partial E(k)}{\partial k} = 0
$$

状態密度
$$
D(E) \propto　\frac{1}{\sqrt{E - E_i}}
$$
$E_i$ は，バンドの極小点または極大点のエネルギー

バンドの極小点の近くでは，分散関係を2次式で近似でき，$E(k) = E_i + a k^2$ ．
ここで $a$ は定数である．

この式から，
$$
E-E_i =a k^2
$$
---

なので
$$
k = \sqrt{\frac{E-E_i}{a}},\, \frac{dE}{dk} = 2ak
$$
状態密度は
$$
\begin{aligned}
D(E) &\propto \frac{1}{|dE/dk|}\\
&\propto \frac{1}{|2ak|}
\end{aligned}
$$
ここで $k = \sqrt{\frac{E-E_i}{a}}$ 
$$
D(E) \propto　\frac{1}{\sqrt{E - E_i}}
$$
となる．

---

$E$ が $E_i$ に近づくと， $\sqrt{E-E_i} \rightarrow 0$, $D(E) \rightarrow \infty$

現実では本当に無限大になるわけないため，グラフに極大値（比較的に大きな値）の形になる．

「非対称に発散する」とは
- $1/\sqrt{E - E_i}$：$E>E_i$極大値となる
- $1/\sqrt{E_i - E}$：$E_i>E$極小値となる

図6.7 ( c )の説明

円周方向の量子化間隔が $\bm{K_1} = \frac{2}{d_t}$ から．
半導体ナノチューブのエネルギーギャップが直径に反比例する
$$
E \propto \frac{1}{d_t}
$$

直径 $d_t$ が大きいほど，量子化された波数線の間隔は狭くなる．

---

**ラマン分光**

ラマン分光とは，物質に光を当てて，出てくる散乱光のエネルギー変化を調べる方法，
$E_\mathrm{in}-E_\mathrm{out}$を調べて物質の中でどのような振動があるかが分かる．

共鳴ラマン分光：

電子がエネルギー $E_1$ の状態から $E_2$ の状態に励起されるとき，必要な光のエネルギーは
$$
h\nu =E_2-E_1
$$
もし $E_1$ と $E_2$ の両方がファンホーブ特異点，
つまり状態密度の大きいエネルギーにあるなら，
その遷移は非常に強くなる．

---

## ミラー指数

結晶中の特定の位置，方位，面は基本的に並進ベクトル $\bm{a},\,\bm{b},\,\bm{c}$ に基づいて表す．

単位格子内の任意の位置は $\bm{r}=u\bm{a}+v\bm{b}+w\bm{c}$ で表す．通常の座標表示は $(u,v,w)$ となる．

面を表すには**ミラー指数**を用いる．

ある面がある面が $a,b,c$ 軸と交わる点を $\frac{\bm{a}}{u},\quad
\frac{\bm{b}}{v},\quad
\frac{\bm{c}}{w}$ である時，その面を $(u\,v\,w)$ とする。

軸と交わらない場合， $\infty = \frac{1}{0}$ とする．

図2.30に示す例であは，
$$
\left( \frac1u\,\frac1v\,\frac1w\right) = \left( \frac12\,\frac13\,\frac14\right)
$$
である．
お互いに素である整数を組み $(h\,k\,l)=(6\,4\,3)$ 書き換えて，この整数の組をミラー指数と呼ぶ．

---

図2.32の面は座標軸と平行な場合，
$$
\left( \frac1u\,\frac1v\,\frac1w\right) = \left( \frac10\,\frac11\,\frac10\right)
$$
なので，ミラー指数 $(h\,k\,l)=(0\,1\,0)$ となる．

### 方向指数

面の方位を表すミラー指数は $[h\,k\,l]$ ，角括弧で表記する．ある方向のベクトル 
$$
\bm{A} = h\bm{a}_1 + k\bm{a}_2 + l\bm{a}_3
$$ 
と表す．

---

### 三方晶・六方晶のミラー指数

ベクトル $\bm{c}$ を回転軸に平行なものとし，
回転軸と直交で角度 $120\mathrm{deg}$ をいなすようなベクトル 
$\bm{a}_1,\,\bm{a}_2,\,\bm{a}_3$ を表すように
**図2.33**
$$
\left(\frac1u\,\frac1v\,\frac1w\,\frac1x\right) 
= \left(\frac12\,\frac1{-1}\,\frac12\,\frac11\right) 
$$
となり，
ミラー指数お互いに素である整数の組 $(h\,k\,l\,m) = (1\,-2\,1\,2)$ と求められる．

---

# 逆格子

## 逆格子空間

結晶は空間的に周期的なので，電子状態や格子振動を波として分解すると非常に自然であり，
その波を表す変数として波数ベクトル $\bm{k}$ を使う．

単振動
$$
A 
= A_0 \sin \left( \omega t + \phi \right)
$$
ここで， $A_0$ は振幅であり， $T$ は周期， $\omega=\frac{2 \pi}{T}$ は角振動数， $\phi$ は初期位相である．

たくさんの振動数を重ね合わせて
$$
A = \sum_n A_n \sin \left( \omega_n t + \phi_n \right)
$$

---

ある瞬間の波は，物理量の空間座標の周期的変動であり， $x$ 軸上の波は
$$
A(x) = A_0 \sin \left( \frac{2\pi x}{\lambda} + \phi \right)
$$
ここで， $\lambda$ は波長である． $k = \frac{2\pi}{\lambda}$ を波数と呼ぶ．

３次元空 $(x,y,z)$ において位置ベクトル $\bm{r} = (x,y,z)$ は波数ベクトル $k= (k_x,k_y,k_z)$ が対応する．

波数ベクトルの意味を考えてみる．
$$
\begin{align*}
A(\bm{r}) &= A_0 \sin \left(\bm{k}\cdot \bm{r} + \phi \right) \\
&= A_0 \sin \left( k_xx+k_yy+k_zz+\phi \right) = \text{一定}
\end{align*}
$$
位置ベクトル $\bm{r}$ と波数ベクトル $\bm{k}$ の内積は定数である．

---

## 逆格子ベクトル
格子点を表すベクトルは
$$
\bm{R}_n = n_1\bm{a}_1 + n_2\bm{a}_2 + n_3\bm{a}_3
$$

### １次元の逆格子点

周期 $a$ の関数
$$
f(x+na)=f(x)
$$
を考える．だたし， $n$ は任意の整数である．
この関数をフーリエ級数で表すと
$$
f(x) = \sum_{m=-\infty}^{\infty} c_m \exp \left(i\frac{2\pi}{a}mx \right)
$$
になる．$c_m$ はフーリエ係数である．

---

$$
\begin{align*}
f(x) &= \sum_{m=-\infty}^{\infty} c_m \exp \left(i\frac{2\pi}{a}m(x+na) \right) \\
&= \sum_{m=-\infty}^{\infty} c_m \exp \left(i\frac{2\pi}{a}mx \right) 
  \exp \left( i2\pi mn \right) \\
&= \sum_{m=-\infty}^{\infty} c_m \exp \left(i\frac{2\pi}{a}mx \right) \\
&= f(x)
\end{align*}
$$
$$
G_m = \frac{2\pi}{a} m \quad \mathrm{m}\text{は任意の整数}
$$
は１次元逆格子点の式である．
$G_m$ を用いて
$$
f(x) = \sum_{G_m} A_{G_m} \exp \left(iG_mx \right)
$$
ここで，$A_{G_m}$ フーリエ変換で求められる．

---

３次元に広がるのは１次元と似てる．３次元の逆格子点は
$$
f(\bm{r}) = \sum_{\bm{G}_m} A_{\bm{G}_m} \exp (i\bm{G}_m \cdot \bm{r})
$$
周期関数であるため，
$$
\begin{align*}
  f(\bm{r}+\bm{R}) 
  &= \sum_{\bm{G}_m} A_{\bm{G}_m} 
    \exp \left\{
      i\bm{G}_m \cdot (\bm{r}+\bm{R})
    \right\}\\
  &= \sum_{\bm{G}_m} A_{\bm{G}_m} 
    \exp (i\bm{G}_m \cdot \bm{r}) 
    \exp (i\bm{G}_m \cdot \bm{R})\\
  &= f(\bm{r})
\end{align*}
$$
が成立する．ここの変形において
$$
\exp (i\bm{G}_m \cdot \bm{R}) = 1
$$
になければならない．

---

すなわち
$$
\begin{align*}
  \bm{G}_m \cdot \bm{R}_n
  &= \bm{G}_m \cdot (
    n_1 \bm{a}_1 + n_2 \bm{a}_2 + n_3 \bm{a}_3
  ) \\
  &= n_1 \bm{G}_m \cdot \bm{a}_1
    + n_2 \bm{G}_m \cdot \bm{a}_2
    + n_3 \bm{G}_m \cdot \bm{a}_3
  \\
  &= 2 \pi N
\end{align*}
$$
となる．だだし， $N$ は整数である．基本並進ベクトル
$\bm{a}_1,\,\bm{a}_2,\,\bm{a}_3$
と逆格子の基本ベクトルの関係
$\bm{b}_1,\,\bm{b}_2,\,\bm{b}_3$
は
$$
\bm{a}_i \cdot \bm{b}_j = 2 \pi \delta_{ij}
$$
である．これは**逆格子の基本ベクトルの性質**である．
デルタ関数を展開してみると
$$
\bm{a}_1 \cdot \bm{b}_1
= 2 \pi 
\frac{
  \bm{a}_1 \cdot (\bm{a}_2 \times \bm{a}_3)
}
{
  \bm{a}_1 \cdot (\bm{a}_2 \times \bm{a}_3)
}
$$
分母はスカラー三重積である．$\bm{a}_1$ で割ると，逆格子の基本ベクトルは
$$
\bm{b}_1
  = 2 \pi 
  \frac{
    \bm{a}_2 \times \bm{a}_3
  }
  {
    \bm{a}_1 \cdot (\bm{a}_2 \times \bm{a}_3)
  },\quad
\bm{b}_2
  = 2 \pi 
  \frac{
    \bm{a}_3 \times \bm{a}_1
  }
  {
    \bm{a}_2 \cdot (\bm{a}_3 \times \bm{a}_1)
  },\quad
\bm{b}_3
  = 2 \pi 
  \frac{
    \bm{a}_1 \times \bm{a}_2
  }
  {
    \bm{a}_3 \cdot (\bm{a}_1 \times \bm{a}_2)
  }
$$

---

**３次元の逆格子点を与える式**
$$
\bm{G}_m = m_1 \bm{b}_1 + m_2 \bm{b}_2 + m_3 \bm{b}_3
$$
は３次元の周期関数がフーリエ級数展開したものである．

**単純立方格子の逆格子点**

単位ベクトルを用いて逆格子点を表す．
まず，基本並進ベクトルとその計算は
$$
\bm{a}_1 = a\bm{e}_x ,\quad
\bm{a}_2 = a\bm{e}_y ,\quad
\bm{a}_3 = a\bm{e}_z \\

\bm{a}_2 \times \bm{a}_3 
= a^2 \bm{e}_y \times \bm{e}_z 
= a^2 \bm{e}_x \\

\bm{a}_1 \cdot (\bm{a}_2 \times \bm{a}_3) 
= a^3 \bm{e}_x \cdot \bm{e}_x 
= a^3
$$
なので，逆格子のベクトルは
$$
\bm{b}_1 = \frac{2\pi}{a} \bm{e}_x ,\quad
\bm{b}_2 = \frac{2\pi}{a} \bm{e}_y ,\quad
\bm{b}_3 = \frac{2\pi}{a} \bm{e}_z 
$$
で与えられる．
１辺の長さが $\frac{2\pi}{a}$ である立方体を単位胞とする単純立方格子の格子点と等しい．

---

面心立方格子の逆格子点

---

# 共有結合

### ダイヤモンドにおける共有結合

ダイヤモンドは炭素のみからなる結晶である．
$(2s)^2(2p)^2$の価電子が結合を担う．
$1s$電子がほぼ接合に寄与しない．

配位数：４．１つの原子に４つの隣接原子がある．
混成軌道理論：４つの結合が等価であることを説明する

<!--
ダイヤモンドは炭素（C）のみからなる結晶
炭素原子の電子配置：(1s)2(2s)2(2p)2(1s)^2(2s)^2(2p)^2
(1s)2(2s)2(2p)2

1s1s
1s 電子＝内殻電子 → 結合にはほぼ寄与しない
$(2s)2(2p)2(2s)^2(2p)^2$
$(2s)2(2p)2$の価電子が結合を担う


結晶構造上の特徴：配位数4（1つのC原子に隣接原子が4つ）
矛盾点：4つの結合はすべて等価なのに、価電子は 2s2s
2s と 2p2p
2p の2種類しかない
→ このままでは4つの等価な結合を説明できない
-->

---

$sp^3$混成軌道：

- $2s$ 電子１個が $2p$ 軌道に移す．
$(2s)^1(2p)^3$ となる．
- この４つの軌道が混成され，４つの等価な軌道を作る．

この「１つの $s$ 軌道と３つの $p$ 軌道」からなるものは
**$sp^3$ 混成軌道**
という．

4つの軌道はいずれも $2s$ 成分と $2p$ 成分を同じ割合で含む

共有結合の方向：
$[1\ 1\ 1]$，$[1\ -1\ -1]$，$[-1\ 1\ -1]$，$[-1\ -1\ 1]$

混成軌道の波動関数の $p$ 軌道の $xyz$ 方向の係数です．

---

## イオン結合

### マーデルング定数

マーデルングエネルギーとは，
イオンを点電荷をみなし，
クーロン力のポテンシャルエネルギーである．

結晶中イオンが距離 $r_{ij} = | \bm{r}_j - \bm{r}_i|$ 
がはなれてるとき，ポテンシャルは
$$
V_{ij} = \frac{Z_i Z_j e^2}{4\pi\varepsilon_0 r_{ij}}
$$
で与えられる．
ここで，$Z_i e$ は $i$ 番目のイオンの電荷，
$\varepsilon_0$ は真空の誘電率である．

**マーデルング定数**：
$i$ 番目のイオンと,
それ以外のすべてのイオンとの間に働くクーロン力によって生じるポテンシャルエネルギーは
$$
V_i = \sum_{j\neq i} V_{ij} 
= \frac{e^2}{4\pi\varepsilon_0}
\sum_{j\neq i}\frac{Z_i Z_j}{r_{ij}}
$$


---

最近接イオンのクーロン力によって生じるポテンシャルエネルギー
$-\dfrac{Z_+Z_- e^2}{4\pi\varepsilon_0 d}$
で上の式を割ったもの
$$
M = 
\frac{d}{Z_+Z_-}
\sum_{j\neq i}\frac{Z_i Z_j}{r_{ij}}
$$
がマーデルング定数と呼ぶ．
マーデルング定数は結晶構造によって値を定まる．
ここで，$Z_+e$  $Z_-e$ 
はそれぞれイオン結晶中の陽イオンと陰イオンの電荷であり，
$d$は最近接イオン間距離である．

例えば，塩化ナトリウム
| 近接順位 | イオン | 個数 | 距離 | Mへの寄与 |
|---|---|---|---|---|
| 最近接 | $\mathrm{Na^+}$ | 6個 | $d$ | $+6$ |
| 第二近接 | $\mathrm{Cl^-}$ | 12個 | $\sqrt{2}d$ | $-12/\sqrt{2}$ |
| 第三近接 | $\mathrm{Na^+}$ | 8個 | $\sqrt{3}d$ | $+8/\sqrt{3}$ |

---

$M > 1$ の意味：
  - 同種イオン間の斥力でエネルギーは増加するはずだが、それでも
  - 孤立した1組のイオン対（距離$d$）よりも結晶全体の方がエネルギーが低い
  - → **分子より結晶の方が安定**（結合エネルギーが大きい）


### 塩化ナトリウムの結合エネルギー

塩化ナトリウムの格子定数 $a = 0.564\,\mathrm{nm}$,
マーデルング定数が $M = 1.748$
であることを用いるとマーデルングエネルギーは
$$
V_i = -\frac{Me^2}{2\pi\varepsilon_0 a} 
= 1.43\times10^{-18}\,\mathrm{J} 
= 8.92\,\mathrm{eV}
$$
と見積もられる．

実際の結晶においては，
イオンどうしが近づくと斥力も働くようになるため，
図6.9に示すように，
ポテンシャルエネルギーはマーデルング定数を用いた見積もりの90\%程度の値になる．

---

**$Na + Cl \rightarrow NaCl$ 結晶のエネルギー変化**
 
$$
\mathrm{Na} \xrightarrow{+5.1\,\mathrm{eV（イオン化）}} \mathrm{Na^+} + e^-
$$
 
$$
e^- + \mathrm{Cl} \longrightarrow \mathrm{Cl^-} + 3.6\,\mathrm{eV（電子親和力）}
$$
 
$$
\mathrm{Na^+} + \mathrm{Cl^-} \longrightarrow \mathrm{NaCl結晶} + 8.1\,\mathrm{eV（格子エネルギー）}
$$
NaClの結合エネルギーは6.6 eV