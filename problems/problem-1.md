---
title: "Problem-1"
start-date: "2024-10-12"
end-date: "None"
page-layout: full
solved: "True"
source: "Ex-1C-6, Pg 24, LADR, 4e"
categories:
  - subspace
  - vector space
  - linear algebra
css: /styles.css
---

- Is $\displaystyle \left\{( a,b,c) \in \mathbb{R}^{3} :\ a^{3} =b^{3}\right\}$ a subspace of $\displaystyle \mathbb{R}^{3}$?

- Is $\displaystyle \left\{( a,b,c) \in \mathbb{R} :\ a^{3} =b^{3}\right\}$ a subspace of $\displaystyle \mathbb{C}^{3}$?

## Solution

We have:

$$
\begin{equation*}
\begin{aligned}
a^{3} & =b^{3}\\
( a-b)\left( a^{2} +ab+b^{2}\right) & =0
\end{aligned}
\end{equation*}
$$

### Set-1

If $\displaystyle a,b\in \mathbb{R}$, then $\displaystyle a=b$ is the only possibility. Therefore, the following set is a subspace:

$$
\begin{equation*}
\left\{( a,b,c) \in \mathbb{R}^{3} :a^{3} =b^{3}\right\} =\left\{( a,a,c) \in \mathbb{R}^{3}\right\}
\end{equation*}
$$

### Set-2

If $\displaystyle a,b\in \mathbb{C}$, in addition to $\displaystyle a=b$, we have $\displaystyle a=zb$ and $\displaystyle a=\overline{z} b$, where $\displaystyle z=\frac{-1+\sqrt{3} i}{2}$.

To see why the other set is not a subspace, let us take two elements $\displaystyle ( 1,z,0)$ and $\displaystyle ( 1,\overline{z} ,0)$ that are in the set. The sum $\displaystyle ( z,1,0) +(\overline{z} ,1,0) =( -1,2,0)$ is not a member of the set. Since this set is not closed under vector addition, it can't be a subspace of $\displaystyle \mathbb{C}^{3}$.

## Notes on the problem

The solution to this problem was direct. I could see the pattern straight away and knew what had to be done here and I didn't have to search for solutions. The solution was immediately available.