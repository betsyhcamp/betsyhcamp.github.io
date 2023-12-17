---
title: "This is a second test post"
date: 2023-12-16
tags: ["initial post", "syntax", "math"]
series: ["Themes Guide"]
ShowToc: true
TocOpen: true
math: mathjax
draft: false
---

# A section

some text here

## A subsection

subsection text here

math here:

$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$


A matrix: 

{{< math >}}
$$
  \begin{bmatrix}
    a & b \\
    c & d \\
    e & f \\
  \end{bmatrix}
$$
{{< /math >}}


```python
from typing import Union
def add_two(num_1:Union[int,float], num_2:Union[int,float])->Union[int,float]:
    """Add two numbers and return the result"""
    return num_1 + num_2

def multiply_two(num_1:Union[int,float], num_2:Union[int,float])->Union[int,float]:
    """Multiply two numbers and return the result"""
    return num_1 * num_2

```