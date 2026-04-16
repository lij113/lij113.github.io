---
icon: fas fa-code
order: 3
---

# Projects

<div class="project-grid">

<article class="project-card">
  <div class="project-header">
    <i class="fas fa-file-powerpoint project-icon"></i>
    <h3><a href="https://github.com/lij113/W2P-Agent" target="_blank">W2P-Agent</a></h3>
  </div>
  <p class="project-desc">AI-powered Word to PPT converter &mdash; fully automated document-to-presentation pipeline using LLM agents.</p>
  <div class="project-tags">
    <span class="tag">Python</span>
    <span class="tag">LLM</span>
    <span class="tag">Automation</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/W2P-Agent" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

<article class="project-card">
  <div class="project-header">
    <i class="fas fa-chart-line project-icon"></i>
    <h3><a href="https://github.com/lij113/EmbeddingAgentMonitor" target="_blank">EmbeddingAgentMonitor</a></h3>
  </div>
  <p class="project-desc">Monitoring system for embedding agents &mdash; real-time tracking and visualization of agent performance metrics.</p>
  <div class="project-tags">
    <span class="tag">Monitoring</span>
    <span class="tag">Embeddings</span>
    <span class="tag">Dashboard</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/EmbeddingAgentMonitor" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

<article class="project-card">
  <div class="project-header">
    <i class="fas fa-crosshairs project-icon"></i>
    <h3><a href="https://github.com/lij113/DeepSniper" target="_blank">DeepSniper</a></h3>
  </div>
  <p class="project-desc">Token calculation and monitoring system for LLM API usage &mdash; track costs and optimize token consumption.</p>
  <div class="project-tags">
    <span class="tag">Token Calculator</span>
    <span class="tag">Monitoring</span>
    <span class="tag">LLM</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/DeepSniper" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

<article class="project-card">
  <div class="project-header">
    <i class="fas fa-shield-alt project-icon"></i>
    <h3><a href="https://github.com/lij113/WebInjection" target="_blank">WebInjection</a></h3>
  </div>
  <p class="project-desc">Web security testing and injection analysis toolkit.</p>
  <div class="project-tags">
    <span class="tag">Security</span>
    <span class="tag">Web</span>
    <span class="tag">Testing</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/WebInjection" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

<article class="project-card">
  <div class="project-header">
    <i class="fas fa-lock project-icon"></i>
    <h3><a href="https://github.com/lij113/Privacy-preservation-in-a-code" target="_blank">Privacy Preservation in Code</a></h3>
  </div>
  <p class="project-desc">Research on privacy-preserving techniques in source code analysis and transformation.</p>
  <div class="project-tags">
    <span class="tag">Privacy</span>
    <span class="tag">Code Analysis</span>
    <span class="tag">Research</span>
  </div>
  <div class="project-links">
    <a href="https://github.com/lij113/Privacy-preservation-in-a-code" target="_blank"><i class="fab fa-github"></i> Source</a>
  </div>
</article>

</div>

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
  gap: 1.2rem;
  max-width: 900px;
}

.project-card {
  border: 1px solid var(--sidebar-border-color, #e1e4e8);
  border-radius: 10px;
  padding: 1.2rem;
  background: var(--sidebar-bg);
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
}

.project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  border-color: #0366d6;
}

.project-header {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  margin-bottom: 0.5rem;
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

.project-icon {
  font-size: 1.3rem;
  color: #0366d6;
}

.project-desc {
  font-size: 0.9rem;
  color: var(--text-muted);
  margin: 0.4rem 0 0.6rem 0;
  line-height: 1.5;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-bottom: 0.7rem;
}

.tag {
  display: inline-block;
  padding: 0.15rem 0.55rem;
  font-size: 0.78rem;
  border-radius: 12px;
  background: rgba(3, 102, 214, 0.1);
  color: #0366d6;
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
