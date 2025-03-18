---
jupytext:
    formats: md:myst
    text_representation:
        extension: .md
        format_name: myst
kernelspec:
    display_name: Python 3
    language: python
    name: python3
---

# 附录G 桁架节点板在斜腹杆压力作用下的稳定计算

## 1. 基本假定

图G.0.1中 ![](media/image1058.svg) 为节点板失稳时的屈折线，其中 ![](media/image1059.svg) 平行于弦杆，![](media/image1060.svg)。

![](media/image1061.jpeg)

（a）有竖杆时                                      （b）无竖杆时  
图G.0.1 节点板稳定计算简图  

在斜腹杆轴向压力 $P$ 的作用下，$a$ 区（$a$ 板件）、$b$ 区（$b$ 板件）和 $c$ 区（$c$ 板件）同时受压，当其中某一区先失稳后，其他区即相继失稳，为此要分别计算各区的稳定。

## 2. 计算方法

### $a$ 区：

$$
\frac{P_a}{f_a} \leq \phi_a \tag{G.0.2-1}
$$

### $b$ 区：

$$
\frac{P_b}{f_b} \leq \phi_b \tag{G.0.2-2}
$$

### $c$ 区：

$$
\frac{P_c}{f_c} \leq \phi_c \tag{G.0.2-3}
$$

式中：

- $t$ —— 节点板厚度；
- $P$ —— 受压斜腹杆的轴向力；
- $l_a$、$l_b$、$l_c$ —— 分别为屈折线 $a$、$b$、$c$ 的长度；
- $\phi_a$、$\phi_b$、$\phi_c$ —— 各受压区板件的轴心受压稳定系数，可按 $b$ 类截面查取；其相应的长细比分别为：  
    $$
    \lambda_a = 2.77 \frac{l_a}{t}, \quad \lambda_b = 2.77 \frac{l_b}{t}, \quad \lambda_c = 2.77 \frac{l_c}{t}
    $$  
    式中 $l_a$、$l_b$、$l_c$ 为 $a$、$b$、$c$ 区受压板件的中线长度；其中 $l_a = l_b$；  
    $l_{a1}$（$l_{a2}$）、$l_{b1}$（$l_{b2}$）、$l_{c1}$（$l_{c2}$）为各屈折线段在有效长度线上的投影长度。

对于 $l > b$ 且沿自由边加劲的无竖腹杆节点板（$b$ 为节点板自由边的长度），亦可用上述方法进行计算，只是仅需验算 $a$ 区和 $b$ 区，而不必验算 $c$ 区。

