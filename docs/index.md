# Mathsforall

Welcome to mathsforall ~ This is a open-sourced website that aims to share the most random ideas I came up with in mathematics!

---

## Latest Updates

This list updates automatically based on the last Git commit.

<div class="annotate">

{% for page in pages | sort(attribute='meta.git_revision_date_localized', reverse=true) | slice(5) %}
- [{{ page.title }}]({{ page.url | url }})
{% endfor %}

</div>

---

<div class="hero">
  <h1>Maths For All</h1>
  <p>A growing collection of mathematical notes, proofs, and explorations.</p>
  <a class="button" href="#explore">Explore Notes</a>
  <a class="button" href="#" onclick="randomDoc()">Random Article</a>
</div>

# <span id="explore"></span> Explore the Notes

## Elementary Analysis

<div class="grid cards" markdown>

- :material-function: **Oblique Asymptotes**  
  Determining the existence of oblique asymptotes from graphs alone.  
  [:octicons-arrow-right-16: Read](notes/Existence_of_OA_discussion.md)

- :material-graph-line: **Power–Exponential Functions**  
  Exploring functions beyond polynomial–exponential behaviour.  
  [:octicons-arrow-right-16: Open](notes/The_function_with_no_graph.md)

</div>

---

## Multivariable Differential Calculus

<div class="grid cards" markdown>

- :material-vector-combine: **The Nature of Dot Product**  
  Understanding projection, geometry, and interpretation of dot products.  
  [:octicons-arrow-right-16: Read](notes/Why_Dot_Product.md)

- :material-compare: **Curvature Under a Time Parameter**  
  A complete proof of the universal curvature formula.  
  [:octicons-arrow-right-16: View Proof](notes/Curvature_time_parametrization_proof.md)

</div>

---

## Algebraic Topology

<div class="grid cards" markdown>

- :material-shape-plus: **Open Sets in Metric Spaces**  
  Proof using open balls and neighbourhood structures.  
  [:octicons-arrow-right-16: Read](notes/proof_open_interior.md)

- :material-shape-outline: **Closed Sets in Metric Spaces**  
  Proof via complementarity and limit points.  
  [:octicons-arrow-right-16: Read](notes/proof_closed_interior.md)

</div>

---

## Proofs of the Basel Problem

<div class="grid cards" markdown>

- :material-sigma: **Euler’s Proof**  
  The classical analytic derivation of  
  \(\sum_{n=1}^\infty \frac{1}{n^2} = \frac{\pi^2}{6}\).  
  [:octicons-arrow-right-16: View Proof](notes/basel_problem_euler.md)

</div>

---

## Project

<div class="grid cards" markdown>

- :material-flask: **Optimization in Logistic Regression**  
  Modifying numerical optimization methods for better convergence.  
  [:octicons-arrow-right-16: Read Project](projects/Optimization.md)

</div>

---

# About

Mathsforall is a garage for my investigations within the field of mathematics (perhaps will explore more in other fields!). The documents are free for all, which means that anyone can use any information available in this website without any consent! I aim to write in a clear and precise manner, that means it might not be rigorous at all times, but I hope everyone finds it easy to understand. If you wish to receive the .tex files please contact me! If you seek any clarification in any of the documents please contact me! If you're just bored and have nobody to talk to please contact me!

# Contact

Email: jimmy.zhy7@gmail.com


![Total Visits](https://visitor-badge.laobi.icu/badge?page_id=Mrle0n7.mathsforall)
