
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
