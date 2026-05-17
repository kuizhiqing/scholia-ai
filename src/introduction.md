# Introduction

Welcome to **Scholia AI** — a personal, AI-augmented notebook of things I'm
learning. Notes here are written as Markdown, rendered with
[mdBook](https://rust-lang.github.io/mdBook/), and math is typeset with
[KaTeX](https://katex.org/) via
[`mdbook-katex`](https://github.com/lzanini/mdbook-katex).

## Math support

Inline math uses single dollar signs: \\( a^2 + b^2 = c^2 \\) renders as
$a^2 + b^2 = c^2$.

Display math uses double dollar signs:

$$
\int_{-\infty}^{\infty} e^{-x^2}\, dx = \sqrt{\pi}
$$

A small example with aligned equations:

$$
\begin{aligned}
\nabla \cdot \mathbf{E} &= \frac{\rho}{\varepsilon_0} \\
\nabla \cdot \mathbf{B} &= 0 \\
\nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
\nabla \times \mathbf{B} &= \mu_0 \mathbf{J} + \mu_0 \varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}
\end{aligned}
$$

## How to read these notes

- Browse the sidebar on the left.
- Use the search icon (top-left) to search across all pages.
- Toggle the theme with the paintbrush icon.
