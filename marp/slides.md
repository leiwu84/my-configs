---
marp: true
paginate: true
math: mathjax
theme: gaia
color: black
backgroundColor: white
# footer: '![width:50](fig/logo.png)'

---
# Presentation Title

Lei Wu

---

# Default Font Size

This slide has the default font size.

---
<style scoped>{font-size: 1.5rem;}</style>

# Smaller Font Size

This slide has a smaller font size.


---
<style scoped>{font-size: 1.5rem;}</style>

## Items Show All

The following items will be shown together at once.

- Item 1
- Item 2
- Item 3

---
<style scoped>{font-size: 1.5rem;}</style>

## Items Show One-By-One

The following items will be shown one-by-one.

* Item 1
* Item 2
* Item 3

---
<style scoped>{font-size: 1.5rem;}</style>

## Horizontal Split 1 Fig


<div style="float: right; margin-left: 20px;">
  <img src="fig/<figname>.png" alt="figname" width="600">
</div>

Some description:

- item 1
- item 2
- item 3


---
<style scoped>{font-size: 1.5rem;}</style>

## Horizontal Split 2 Figs

<div style="float: left;">

  <div style="float: top; margin-left: 160px">
    Fig 1 Title
  </div>

  <img src="fig/<figname_1.png>" alt="figname_1" width="550">
</div>

<div style="float: right;">
  <div style="float: top; margin-left: 160px">
    Fig 2 Title
  </div>

  <img src="fig/<figname_2.png>" alt="figname_1" width="550">
</div>


---
<style scoped>{font-size: 1.5rem;}</style>

## Math Equations

In-line: angle = $30^{\circ}$.

Block:

$$
\begin{align}
&v_1 \rightarrow V_{1, \min}, V_{1, \max} \\
&v_2 \rightarrow V_{2, \min}, V_{2, \max} \\
    &\vdots \\
&v_m \rightarrow V_{m, \min}, V_{m, \max}
\end{align}
$$
