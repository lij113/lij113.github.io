---
icon: fas fa-flask
order: 2
---

# Publications

<div class="publications">

## 2026

<article class="publication-item">
  <div class="pub-content">
    <h3>SynthFix: Hybrid Neural-Symbolic Framework for Automated Code Vulnerability Repair</h3>
    <p class="pub-authors">Yifan Zhang, <strong>Jieyu Li</strong>, Kexin Pei, Yu Huang, Kevin Leach</p>
    <p class="pub-venue"><em>Findings of the Association for Computational Linguistics (<strong>ACL 2026</strong>)</em></p>
    <p class="pub-desc">A hybrid framework combining Supervised Fine-Tuning (SFT) and Proximal Policy Optimization (PPO) for automated repair of code vulnerabilities.</p>
    <div class="pub-links">
      <a href="https://openreview.net/forum?id=" target="_blank" class="btn btn-sm"><i class="fas fa-file-pdf"></i> Paper</a>
    </div>
  </div>
</article>

</div>

<style>
.publications {
  max-width: 800px;
}

.publication-item {
  position: relative;
  border-left: 4px solid #0366d6;
  padding: 1rem 1.5rem;
  margin-bottom: 1.5rem;
  background: linear-gradient(135deg, rgba(3, 102, 214, 0.04), transparent);
  border-radius: 0 10px 10px 0;
  transition: border-color 0.2s ease, background 0.2s ease;
}

.publication-item:hover {
  border-left-color: #2ea44f;
  background: linear-gradient(135deg, rgba(46, 164, 79, 0.06), transparent);
}

.pub-content h3 {
  margin: 0 0 0.4rem 0;
  font-size: 1.08rem;
  line-height: 1.4;
}

.pub-authors {
  color: var(--text-muted);
  margin: 0.2rem 0;
  font-size: 0.92rem;
}

.pub-authors strong {
  color: var(--text-color);
}

.pub-venue {
  margin: 0.3rem 0;
  font-size: 0.9rem;
}

.pub-desc {
  margin: 0.5rem 0;
  font-size: 0.92rem;
  color: var(--text-muted);
  line-height: 1.6;
}

.pub-links {
  margin-top: 0.6rem;
}

.pub-links .btn {
  display: inline-block;
  padding: 0.3rem 0.8rem;
  font-size: 0.85rem;
  border-radius: 6px;
  text-decoration: none;
  color: #fff;
  background: linear-gradient(135deg, #0366d6, #0256b9);
  transition: opacity 0.15s ease, transform 0.15s ease;
}

.pub-links .btn:hover {
  opacity: 0.9;
  transform: translateY(-1px);
}
</style>
