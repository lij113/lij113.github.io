---
icon: fas fa-code
order: 3
---

# Projects

<div class="project-grid">

<article class="project-card">
  <div class="project-header">
    <div class="project-icon-wrap" style="background: linear-gradient(135deg, #ff6b6b, #ee5a24);">
      <i class="fas fa-file-powerpoint"></i>
    </div>
    <h3><a href="https://github.com/lij113/W2P-Agent" target="_blank">W2P-Agent</a></h3>
  </div>
  <p class="project-desc">AI-powered Word to PPT converter &mdash; fully automated document-to-presentation pipeline using LLM agents.</p>
  <div class="project-tags">
    <span class="tag" style="--tag-color: #ee5a24;">Python</span>
    <span class="tag" style="--tag-color: #0366d6;">LLM</span>
    <span class="tag" style="--tag-color: #2ea44f;">Automation</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/W2P-Agent" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

<article class="project-card">
  <div class="project-header">
    <div class="project-icon-wrap" style="background: linear-gradient(135deg, #a29bfe, #6c5ce7);">
      <i class="fas fa-chart-line"></i>
    </div>
    <h3><a href="https://github.com/lij113/EmbeddingAgentMonitor" target="_blank">EmbeddingAgentMonitor</a></h3>
  </div>
  <p class="project-desc">Monitoring system for embedding agents &mdash; real-time tracking and visualization of agent performance metrics.</p>
  <div class="project-tags">
    <span class="tag" style="--tag-color: #6c5ce7;">Monitoring</span>
    <span class="tag" style="--tag-color: #0366d6;">Embeddings</span>
    <span class="tag" style="--tag-color: #2ea44f;">Dashboard</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/EmbeddingAgentMonitor" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

<article class="project-card">
  <div class="project-header">
    <div class="project-icon-wrap" style="background: linear-gradient(135deg, #fdcb6e, #e17055);">
      <i class="fas fa-crosshairs"></i>
    </div>
    <h3><a href="https://github.com/lij113/DeepSniper" target="_blank">DeepSniper</a></h3>
  </div>
  <p class="project-desc">Token calculation and monitoring system for LLM API usage &mdash; track costs and optimize token consumption.</p>
  <div class="project-tags">
    <span class="tag" style="--tag-color: #e17055;">Token Calculator</span>
    <span class="tag" style="--tag-color: #0366d6;">LLM</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/DeepSniper" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

<article class="project-card">
  <div class="project-header">
    <div class="project-icon-wrap" style="background: linear-gradient(135deg, #00b894, #00cec9);">
      <i class="fas fa-shield-alt"></i>
    </div>
    <h3><a href="https://github.com/lij113/WebInjection" target="_blank">WebInjection</a></h3>
  </div>
  <p class="project-desc">Web security testing and injection analysis toolkit.</p>
  <div class="project-tags">
    <span class="tag" style="--tag-color: #00b894;">Security</span>
    <span class="tag" style="--tag-color: #0366d6;">Web</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/WebInjection" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

<article class="project-card">
  <div class="project-header">
    <div class="project-icon-wrap" style="background: linear-gradient(135deg, #fd79a8, #e84393);">
      <i class="fas fa-lock"></i>
    </div>
    <h3><a href="https://github.com/lij113/Privacy-preservation-in-a-code" target="_blank">Privacy Preservation in Code</a></h3>
  </div>
  <p class="project-desc">Research on privacy-preserving techniques in source code analysis and transformation.</p>
  <div class="project-tags">
    <span class="tag" style="--tag-color: #e84393;">Privacy</span>
    <span class="tag" style="--tag-color: #0366d6;">Code Analysis</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/Privacy-preservation-in-a-code" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

</div>

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 1.2rem;
  max-width: 900px;
}

.project-card {
  border: 1px solid var(--sidebar-border-color, #e1e4e8);
  border-radius: 12px;
  padding: 1.3rem;
  background: var(--sidebar-bg);
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.08);
  border-color: transparent;
}

.project-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 0.6rem;
}

.project-icon-wrap {
  width: 36px;
  height: 36px;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}

.project-icon-wrap i {
  color: #fff;
  font-size: 0.95rem;
}

.project-header h3 {
  margin: 0;
  font-size: 1.05rem;
}

.project-header h3 a {
  text-decoration: none;
  color: var(--link-color, #0366d6);
}

.project-header h3 a:hover {
  text-decoration: underline;
}

.project-desc {
  font-size: 0.88rem;
  color: var(--text-muted);
  margin: 0.3rem 0 0.7rem 0;
  line-height: 1.55;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.35rem;
  margin-bottom: 0.7rem;
}

.tag {
  display: inline-block;
  padding: 0.15rem 0.55rem;
  font-size: 0.75rem;
  border-radius: 12px;
  background: color-mix(in srgb, var(--tag-color, #0366d6) 12%, transparent);
  color: var(--tag-color, #0366d6);
  font-weight: 500;
}

.project-links a {
  font-size: 0.88rem;
  text-decoration: none;
  color: var(--text-muted);
  transition: color 0.15s ease;
}

.project-links a:hover {
  color: #0366d6;
}
</style>
