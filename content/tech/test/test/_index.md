---
title: "测试代码"
weight: 99999
---


## 当前发布的随笔




### 新增样式

加粗字体的**彩色效果**

```
b, strong {
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    --strong-gradient: linear-gradient(62deg,#188bfd,#a03bff)!important;
    background-image: var(--strong-gradient);
    font-weight: bolder;
}

```