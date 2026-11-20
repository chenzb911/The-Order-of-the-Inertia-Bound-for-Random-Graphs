# The Order of the Inertia Bound for Random Graphs

**Zhengbo Chen and Xiao-Dong Zhang**  
School of Mathematical Sciences, MOE-LSC, SHL-MAC, Shanghai Jiao Tong University, Shanghai 200240, China

Preprint · Manuscript dated **20 November 2026**  
Corresponding author: [Xiao-Dong Zhang](mailto:xiaodong@sjtu.edu.cn)

**[Read the paper (PDF)](paper.pdf)** · [Direct PDF link](https://raw.githubusercontent.com/chenzb911/The-Order-of-the-Inertia-Bound-for-Random-Graphs/main/paper.pdf) · [LaTeX source](paper.tex) · [BibTeX](citation.bib)

## Abstract

For an $n$-vertex graph $G$, let $n_{\geq0}(G)$ be the minimum number of nonnegative eigenvalues among zero-diagonal Hermitian matrices supported on $G$, allowing zero edge weights. For $n\geq2$ and $G\sim G(n,1/2)$, we prove $n_{\geq0}(G)\geq c_2n/\log(2n)$ with probability at least $1-\exp(-c_1n\log(2n))$, where $c_1,c_2>0$ are absolute constants. This proves a Hermitian extension of the Kwan–Wigderson conjecture. With high probability, $n_{\geq0}(G)=\Theta(n/\log n)$ and $n_{\geq0}(G)/\alpha(G)=\Theta(n/(\log n)^2)$, where $\alpha(G)$ is the independence number.

Using Alon's constructions, we obtain, for every sufficiently large $n$, an $n$-vertex graph $G$ with $\alpha(G)=2$ and $n_{\geq0}(G)=\Omega(n^{1/3})$. For infinitely many $n$, we also obtain $n$-vertex graphs $H$ with Shannon capacity $3$ and $n_{\geq0}(H)=\Omega(n^{1/4})$.

## Files and version

- [`paper.pdf`](paper.pdf): current manuscript, dated 20 November 2026.
- [`paper.tex`](paper.tex): LaTeX source for the current manuscript.
- [`citation.bib`](citation.bib) and [`CITATION.cff`](CITATION.cff): citation metadata.

The existing ZIP archive contains an earlier manuscript. Use `paper.pdf` and `paper.tex` for the current version.

## Citation

Zhengbo Chen and Xiao-Dong Zhang. *The Order of the Inertia Bound for Random Graphs*. Preprint, manuscript dated 20 November 2026.

```bibtex
@unpublished{ChenZhang2026Inertia,
  author = {Chen, Zhengbo and Zhang, Xiao-Dong},
  title  = {The Order of the Inertia Bound for Random Graphs},
  year   = {2026},
  month  = nov,
  note   = {Preprint; manuscript dated 20 November 2026},
  url    = {https://github.com/chenzb911/The-Order-of-the-Inertia-Bound-for-Random-Graphs}
}
```

## Build from source

With a LaTeX installation that includes `latexmk`, run:

```sh
latexmk -pdf paper.tex
```
