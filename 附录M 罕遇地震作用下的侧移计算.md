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



# 附录M 罕遇地震作用下的侧移计算

罕遇地震作用下的侧移可按下列公式计算：

当 ![公式](media/image1206.svg) 时：
$$
\Delta_u = \Delta_{ue} \cdot \eta \tag{M-1}
$$

当 ![公式](media/image1208.svg) 时：
$$
\Delta_u = \Delta_{ue} \cdot \eta \cdot \frac{T}{T_g} \tag{M-2}
$$

$$
\Delta_u = \Delta_{ue} \cdot \eta \cdot \frac{T_g}{T} \tag{M-3}
$$

式中：  
$T$ —— 结构自振周期；  
$T_g$ —— 特征周期；  
$\beta_e$ —— 多遇地震作用下水平地震影响系数最大值；  
$\beta_u$ —— 罕遇地震作用下水平地震影响系数最大值；  
$\Delta_{ue}$ —— 多遇地震作用下楼层内最大的弹性层间位移；  
$\Delta_u$ —— 罕遇地震作用下楼层内最大的弹塑性层间位移；  
$\eta$ —— 二阶效应系数，按本规范第5.1.6条的规定采用。

**注：** 计算支撑结构的 $\Delta_{ue}$ 时，应考虑支撑屈曲后的刚度折减。



