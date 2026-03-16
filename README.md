# Qulinecier

Hi! I am Yuting Huang, currently a mathematics (MSci) student from Imperial College.

Here are my projects!

## Formalizing Mathematics/Computing Theory in Lean

- <font size =3>Formalizing Asymptotic Optimality for Convergence of Likelihood</font>

    Check here: [LeanMLE](https://github.com/Qulinecier/LeanMLE)

    This project formalizes classical results from likelihood estimator based the Lean theorem prover and the mathlib mathematical library.
    <details>
    <summary>Info</summary>
    
    <font size =4>Formalizing Asymptotic Optimality for Convergence of Likelihood</font>

    This project formalizes classical results from likelihood estimator based the Lean theorem prover and the mathlib mathematical library.

    <font size =3>Main theorems</font>

    Theorem 1. (Formalized) Assumptions (1-4) in Section 3 are assumed. Then there exists an estimator sequence $(\hat{\theta}_n)$ such that for every radius $a \in(0, \infty)$,


    $$P_{\theta_0}(|\hat{\theta}_n-\theta_0|<a \text { and } \ell_n^{\prime}(\hat{\theta}_n)=0) \rightarrow 1 \quad(n \rightarrow \infty)$$


    where $\ell_n^{\prime}(\hat{\theta}_n)$ denotes the derivative with respect to $\theta$ of the map $\theta \mapsto \rightarrow \ell_n(\theta ; \omega)$, evaluated at $\theta=\hat{\theta}_n(\omega)$.

    Theorem 2. (Planned) Suppose that $X_1, \ldots, X_n$ are iid and satisfy regularity assumptions.

    Then, any consistent sequence $\hat{\theta}_n=\hat{\theta}_n\left(X_1, \ldots, X_n\right)$ of roots of the likelihood equation satisfies

    $$\sqrt{n}\left(\hat{\theta}_n-\theta\right) \xrightarrow{\mathcal{L}} N\left(0, \frac{1}{I(\theta)}\right) .$$

    <font size =3>Library dependency</font>
    1. [Mathlib 4](https://github.com/leanprover-community/mathlib4)
    2. [CLT](https://github.com/RemyDegenne/CLT/tree/master) for Central limit theorem

    <font size =3>Reference</font>

    [1] E. L. Lehmann. Theory of Point estimation. Springer, 2014.<br>
    [2] CLT, https://github.com/RemyDegenne/CLT/tree/master`
    </details>

- <font size =3>Formalization of Frankl – Ray-Chaudhuri – Wilson type intersection theorems in Lean</font>

    Check here: [Ray_Chaudhuri_Wilson](https://github.com/Qulinecier/Ray_Chaudhuri_Wilson)

    This is a formalization of Ray-Chaudhuri – Wilson type intersection theorem and (modular) Frankl - Wilson theorem in Lean 4.

    <details>
    <summary>Theorem</summary>

    Let $L$ be sets of non-negative integers less than a prime number $p$ so that each $L_i$ have size no greater than $s$. Assume that $\mathcal{J}=\{A_1, \ldots, A_m\}$ is a family of subsets of a set of $n$ elements, so that:
    1. $|A_i| \notin L_i+p \mathbf{Z}$
    2. $|A_i \cap A_j| \in L_i+p \mathbf{Z}, \quad j<i$

    Then we have

    $$|\mathcal{T}| \leq \sum_{i=0}^s\binom{n}{i}.$$
    <font></font>
    </details>
- <font size =3>Formalizing CNF structure of Kochen–Specker SAT in Lean</font>

    Check here: [KochenSpeckerSAT](https://github.com/Qulinecier/KS_SAT)

    Formalization of the CNF encoding for the Kochen–Specker theorem (KS) SAT problem with graphs based on the CNF structure, Trestle, in Lean for rigorous proof of the constraints.

## Projects for fun 🎨

### Obsidian Plugin

- Latex font control: [Obsidian-Latex-Style](https://github.com/Qulinecier/Obsidian-Latex-Style)
- Easy text color: [Obsidian-begin-format](https://github.com/Qulinecier/Obsidian-begin-format)
- Drawing plugin: incoming

### Mathematics
- Groups in object oriented programming: [BasicGroup](https://github.com/Qulinecier/BasicGroup)