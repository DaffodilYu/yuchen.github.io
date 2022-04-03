---
title: "Group theory"
collection: learning
type: "Mathematics"
permalink: /2022-01-group_theory
date: 2022-04-01
location: "Napoli, Italy"
---
Group Theory and Quantum Mechanics - Michael Tinkham <img src='https://qph.cf2.quoracdn.net/main-qimg-45b38772bcc40d88c3b88a7b2f3ce055-pjlq'>

I ever read his book on supperconductivity. I just known this book.

Dresselhaus’ book on Group Theory



## Basic concept

**Rotation** 

If the coordinate is rotated by $\theta$ (anti-clockwise), R is
$$
R = \left[ \begin{array}{ll} 
cos(\theta) & -sin(\theta)\\
sin(\theta) & cos(\theta)
\end{array} \right]
$$
**Subgroups and cosets**

	- The cosets cannot be a subgroup since they don't include the identity element.
	- A coset contains no elements in common with the subgroup.



Examples of finite order

- **Vierrergruppe** (A,B,C,E)

 is a group of order 4, representing the rotational-symmetry group of a rectangular solid if A,B,C are taken to be the rotations by $\pi$ about the three orthogonal symmetry axes.

- group of primer order

  cyclic Abelian groups

- Permutation groups (of factorial order)

  The permutation group plays an important role in quantum theory because of Hamiltonian invariant under permutation of the particles.

**Conjugate Elements and Class Structure**



## 大话群论

### 跋 物以类聚，人以群分

群是有结构的元素的集合。群论研究集合的结构特征及其生成规律。

### 第一回 群的基本概念

定义，定理，性质，分类

《群论及其在物理学中的应用导论--李新征》的讲义比较概要：

----

6个定义:

1）群，2) 群的阶、有限群、无限群，3) Abel 群，4) 子群，5) 循环子群与群元的阶，6) 陪集。

3个定理:1) 重排定理， 2) 陪集定理，3) 拉格朗日定理。

**重排定理**：设G = {⋯，gα，⋯}，对∀u ∈ G，当$g_α$取遍G中所有元素时， $ug_α$给出且仅仅一次给出G中所有元素。

群的例子：空间反演群，n阶置换群$S_n$，D3群，n阶循环群（Abel群），

**陪集定理:** 子群的两个陪集非此即彼。设群H是群G的子群，则H的两个左(或右)陪集或者完全相同，或者没有任何公共元素。

**拉格朗日定理**：有限群子群的阶，必为群阶的因子。

如D3群的子群：{e}、G、{e、 d、f}、{e、a}、{e、b}、{e、c}，这些子群的阶分别是 1、6、3、2、2、2，都是 6 的因子。

-----

**类与不变子群**

如果只根据群的定义，乘法表用起来不方便，所以要研究群的构造，把具有某些类似性质的群归为一类。

轭者，驾车时搁在牛马颈上的曲木。双牛（马）共轭，左右并行。

**共轭**. 具有相互性，传递性。

**类**：群G 中所有相互共轭的元素形成的集合，称为群G的一个类。

**类群阶定理**：有限群的每个类中元素的个数都是群阶的因子。

**共轭子群**.  **正规子群**(或**不变子群**)

**正规子群重排定理**

**商群**：G/H

## Books and notebooks

《群论及其在物理学中的应用导论--李新征》

### 群的基本概念及定理

1. 

同构，同态.   **Isomorphism** homomorphism？



3. 
4. 设 H 是 G 的不变子群，那么对任意固定的 f 属于 G，当hα取遍 H 中所有元素的时候，fhαf−1给出且仅仅一次给出 H 中所有元素。
5. 不变子群的左陪集与右陪集是重合的。
6. ，即:



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

**The group rearrangement theorem**

**Linear Algebra and Vector** **Spaces**

**Linear** **vector** **space**
