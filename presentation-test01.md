---
title: Marp is awesome
description: An example slide deck created using Marpit
paginate: true
marp: true
class: invert
math: mathjax
style: |
    .columns {
        display: grid;
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 1rem;
    }
    .h1 {
        text-align: center;
    }
---

# Marp slide deck
## It will blow your f*& mind :rocket:  &#x1F92F; <!-- fit -->
<span style="color:grey">By: </span> Chris

---

# new slide
![bg right](https://picsum.photos/720?image=29)
- one
- two
- three

---
<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>

<!-- _class: inverted-->
<!-- _color: black-->
# SVG
![w:840 h:440 center](assets/wp4_pipeline.svg)



---



# Code

```python
    from pydantic import BaseModel

    class Lover(BaseModel):
        name: str
        age: int

    def fetch_love(lovers: List[Lover], seed: int):
        """TODO"""
        if seed < len(lovers):
            return lovers[seed]
        else
            return None
```

---

# Maths
Some maths I like 
$\lambda = \frac{1}{\sqrt{2\pi}\sigma} \times e^{0.5 \times \left(\frac{(x-\mu)}{\sigma}\right)^2}$

and more I dislike
$$
\begin{align}
x &= Sapiens \\
Sapiens &= Stupid \\
x &= Stupid
\end{align}
$$

---
<!--_color: darkred-->
<!--_backgroundColor: black-->
# <!--fit--> Impact

---

# Two text columns

<div class="columns">
<div>

* a*
* b-
* c=

</div>

<div>

- f*
- t-
- crtrtg=

</div>

