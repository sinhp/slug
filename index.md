---
layout: default
---

<div class="home">
  <h1 class="page-heading">SLUG - Stockholm Lean User Group</h1>
  
  <div class="intro">
    <p>Welcome to the Stockholm Lean User Group (SLUG)! We are a community of enthusiasts interested in the <a href="https://lean-lang.org/">Lean theorem prover</a> and formal mathematics.</p>
    
    <p>Lean is a modern theorem prover and programming language developed by Microsoft Research. It's designed to make formal verification more accessible and is increasingly used in mathematics research and education.</p>
  </div>

  <h2>About SLUG</h2>
  <p>The Stockholm Lean User Group brings together researchers, students, and practitioners interested in:</p>
  <ul>
    <li>Formal mathematics and theorem proving</li>
    <li>The Lean programming language and proof assistant</li>
    <li>Mathematical formalization projects</li>
    <li>Educational applications of formal methods</li>
  </ul>

  <h2>Getting Started with Lean</h2>
  <p>New to Lean? Here are some great resources to get started:</p>
  <ul>
    <li><a href="https://lean-lang.org/">Official Lean website</a></li>
    <li><a href="https://leanprover-community.github.io/">Lean Community</a></li>
    <li><a href="https://leanprover.github.io/theorem_proving_in_lean4/">Theorem Proving in Lean 4</a></li>
    <li><a href="https://github.com/leanprover-community/mathlib4">Mathlib - Lean's mathematical library</a></li>
  </ul>

  <h2>Contact</h2>
  <p>Interested in joining SLUG or learning more? Feel free to reach out!</p>
  
  <h2>Related Projects</h2>
  <p>Check out some Lean-related projects by our community members:</p>
  <ul>
    <li><a href="https://github.com/sinhp/groupoid_model_in_lean4">Groupoid Model in Lean4</a></li>
    <li><a href="https://github.com/sinhp/Poly">Polynomial Functors in Lean4</a></li>
    <li><a href="https://github.com/sinhp/LeanFibredCategories">Fibred Categories in Lean4</a></li>
    <li><a href="https://github.com/sinhp/displayed_categories">Displayed Categories in Lean4</a></li>
  </ul>

  {% if site.posts.size > 0 %}
  <h2>Latest News</h2>
  <ul class="post-list">
    {% for post in site.posts limit: 5 %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
      </li>
    {% endfor %}
  </ul>
  {% endif %}
</div>