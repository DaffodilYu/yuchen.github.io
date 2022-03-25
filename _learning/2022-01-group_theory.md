---
title: "Group theory"
collection: learning
type: "Group theory"
permalink: /2022-01-group_theory
venue: " University of Naples &quotFederico II&quot, Department of Physics"
date: 2022-01-02
location: "Napoli, Italy"
---



## Books and notebooks

《群论及其在物理学中的应用导论--李新征》

### 群的基本概念及定理

1. 群是元素，操作的集合。满足封闭性，结合律，单位元素，逆元素。
2. 群的阶
3. 重排定理
4. 群的例子：空间反演群，n阶置换群，D3群，n阶循环群（Abel群），
5. 子群。如绕固定轴k转动的元素形成的群$\{C_{\vec{k}}(\Psi)\}$，是绕轴上某一点转动(过这点可以有无数个轴)的群 SO(3)群的子群。
6. 群元的阶:对任意一个有限群G，从中取一个元素a，从a出发作幂操作， 总是可以构成G的一个循环子群Zk的，这个Zk等于{a、a2、 ⋯ 、ak−1、ak = e}， 这时称k(满足这个性质的最小的k)为群元a的阶。
7. 陪集:设H是群G的子群，H = {hα}，由固定的g ∈ G，可生成子群H的左 陪集:gH = {ghα|hα ∈ H}，也可生成子群H的右陪集:Hg = {hαg|hα ∈ H}。
8. 陪集定理:设群H是群G的子群，则H的两个左(或右)陪集或者完全相同，或者没有任何公共元素。
9. 拉格朗日(Lagrange)定理:有限群子群的阶，必为群阶的因子。

如D3群的子群：{e}、G、{e、 d、f}、{e、a}、{e、b}、{e、c}，这些子群的阶分别是 1、6、3、2、2、2，都是 6 的因子。

主要是6个定义，3个定理：
1) 群，2) 群的阶、有限群、无限群，3) Abel 群，4) 子群，5) 循环子群与群元的阶，6) 陪集。三个定理:1) 重排定理， 2) 陪集定理，3) 拉格朗日定理。

同构，同态.   **Isomorphism** homomorphism？


### 类与不变子群
1. 共轭:所谓共轭，指的是群G中两个元素f、h，如果在G中存在一个g，使 得f、h可以通过gfg−1 = h联系起来，则称f、h共轭，记为f~h。
2. 类:群 G 中所有相互共轭的元素形成的集合，称为群 G 的一个类。
  - 一个群中的单位元素自成一类，因为对任意 f 属于 G，fef−1 = e;
  - Abel 群的所有元素都自成一类，因为对任意 f 属于 G，取任意 h 属于 G，做hfh−1 = hh−1f = f;
  - 设群元素 f 的阶为 m，即fm = e，则与它同类的元素的阶也为 m。
3. 有限群的每个类中元素的个数都是群阶的因子。
4. 共轭子群:设H和K是群G的两个子群，若存在g属于G，使得K= gHg−1 = {ghg−1|h ∈ H}。这时，称 H 和 K 是共轭子群。
5. 设 H 是 G 的子群，如果 H 中所有元素的同类元素都属于 H，则称 H 是 G 的不变子群(数学上一般称为正规子群)。
6. 设 H 是 G 的不变子群，那么对任意固定的 f 属于 G，当hα取遍 H 中所有元素的时候，fhαf−1给出且仅仅一次给出 H 中所有元素。
7. 不变子群的左陪集与右陪集是重合的。
8. 商群: 设群 G 有不变子群 H，由 H 将 G 分为${g_0H、g_1H、g_2H、...、 g_ iH、...}$，把其中每个陪集看成一个新的元素，并由两个陪集中元素相乘得到另 一陪集中的元素，定义新的元素乘法，即:

陪集串 → 新元素

$g_0 H$         $f_0$

$g_1 H$         $f_1$

$g_2 H$         $f_2$

.......

乘法规则对应关系:

$g_ih_αg_jh_β = g_kh_γ$    $f_i f_j = f_k$

这样得到的群{f0、f1、...、fi、...}称为 G 对其不变子群 H 的商群，记为 G/H。

我们可以把商群当成是群本身，以不 变子群及其陪集为基本单元的一种超结构。

### 同构与同态
1. 若从群 G 到群 F 上，存在一一对应的满映射Φ，且这个映射本身保持 群的乘法运算规律不变，也就是说 G 中两个元素乘积的映射，等于群 G 中两个元素映射的乘积，则称群 G 与群 F 同构，记作 G≅F。映射Φ称为同构映射，它的作用是
2. 变换群
3. 直积与半直积


## 群表示理论
1. 等价表示、不可约表示、酉表示
2. 群代数与正则表示
3. 有限群表示理论
4. 特征标理论
5. 新表示的构成


## 点群与空间群
1. 第一类点群 和 第二类点群
2. 晶体点群与空间群
3. 晶体点群的不可约表示


## 群论与量子力学
1. 哈密顿算符群与相关定理
2. 微扰引起的能级分裂
3. 投影算符与久期行列式的对角化
4. 矩阵元定理与选择定则、电偶极跃迁
5. 红外、拉曼谱、和频光谱
6. 平移不变性与 Bloch 定理
7. 布里渊区与晶格对称性
8. 时间反演对称性


## 转动群
1. SO(3)群与二维特殊酉群 SU(2)
2. SO(3)群与 SU(2)群的不可约表示
3. 双群与自旋半奇数粒子的旋量波函数
4. Clebsch-Gordan 系数

## 置换群
1. n 阶置换群
2. 杨盘及其引理
3. 多电子原子本征态波函数



## 《物理学中的对称性--艾立阿特 道伯尔 仝道荣》

宇称与选择定则

**Conjugate** **elements and classes**

The class structure of product groups

**2.9 The group rearrangement theorem**



### Ch3 **Linear Algebra and Vector** **Spaces**

#### **3.1** **Linear** **vector** **space**

linearly independent

We denote the dimension by the symbol s. (N.B . The dimension is not the number of vectors in L.)

orthogonality

The positive square root $(r, r) ^\frac{1}{2}$ is called the 'norm' (or length) of the vector r.

Kronecker delta

A set of vectors which are each normalised and mutually orthogonal is called an **'orthonormal'** set.

a 'subspace' $L_1$

'orthogonal complement' to $L_1$
