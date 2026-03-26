<template>
  <div class="page">
    <header class="navbar">
      <div class="brand">Shiyi</div>
      <nav class="nav-links">
        <a href="#about">关于</a>
        <a href="#skills">技能</a>
        <a href="#projects">项目</a>
        <a href="#contact">联系</a>
      </nav>
    </header>

    <main>
      <section class="hero section">
        <div class="hero-text">
          <p class="hero-tag">Programmer / Learner / Builder</p>
          <h1>你好，我是拾忆</h1>
          <p class="hero-desc">
            我正在持续学习前端开发、Python 与工程化实践，
            也在一步步搭建属于自己的程序员个人品牌网站。
          </p>
          <div class="hero-actions">
            <a class="btn primary" href="#projects">查看项目</a>
            <a class="btn secondary" href="#contact">联系我</a>
          </div>
        </div>

        <div class="hero-card">
          <h3>当前状态</h3>
          <ul>
            <li>正在学习：Vue 3 + Vite</li>
            <li>关注方向：前端 / Python / 数据相关开发</li>
            <li>目标：持续积累作品与技术输出</li>
          </ul>
        </div>
      </section>

      <section id="about" class="section">
        <div class="section-header">
          <p class="section-tag">About</p>
          <h2>关于我</h2>
        </div>
        <div class="about-card">
          <p>
            我是一名正在持续成长中的开发者，目前在系统学习前端开发与项目实践。
            我希望通过这个网站记录自己的学习路径、展示项目成果，并逐步建立个人技术品牌。
          </p>
          <p>
            这个网站本身也会作为我的长期项目，从基础页面开始，后续逐步加入博客、项目详情、
            深色模式、响应式优化等功能。
          </p>
        </div>
      </section>

      <section id="skills" class="section">
        <div class="section-header">
          <p class="section-tag">Skills</p>
          <h2>技能栈</h2>
        </div>
        <div class="skills-grid">
          <div class="card">
            <h3>前端</h3>
            <p>HTML / CSS / JavaScript / Vue 3 / Vite</p>
          </div>
          <div class="card">
            <h3>编程语言</h3>
            <p>Python / JavaScript</p>
          </div>
          <div class="card">
            <h3>工具链</h3>
            <p>Git / GitHub / VS Code / Vercel</p>
          </div>
          <div class="card">
            <h3>正在学习</h3>
            <p>工程化、组件化开发、个人项目部署</p>
          </div>
        </div>
      </section>

      <section id="projects" class="section">
        <div class="section-header">
          <p class="section-tag">Projects</p>
          <h2>项目展示</h2>
        </div>
        <div class="projects-grid">
          <article class="card project-card">
            <h3>个人主页网站</h3>
            <p>
              使用 Vue 3 + Vite 构建的个人品牌网站，
              作为长期迭代项目，持续完善页面结构和展示内容。
            </p>
            <span class="project-label">Vue 3 / Vite</span>
          </article>

          <article class="card project-card">
            <h3>HRD 前端项目</h3>
            <p>
              一个围绕样本管理、分析流程与结果展示的前端项目，
              用于练习页面设计、组件拆分与前后端对接思路。
            </p>
            <span class="project-label">Vue / Element Plus</span>
          </article>

          <article class="card project-card">
            <h3>车牌识别项目</h3>
            <p>
              基于 Python、YOLO 与 OCR 的识别练习项目，
              用于积累计算机视觉与工程实现经验。
            </p>
            <span class="project-label">Python / YOLO / OCR</span>
          </article>
        </div>
      </section>

      <section id="contact" class="section">
        <div class="section-header">
          <p class="section-tag">Contact</p>
          <h2>联系我</h2>
        </div>
        <div class="contact-card">
          <p>欢迎通过下面的方式找到我。</p>
          <ul class="contact-list">
            <li><strong>GitHub：</strong> your-github-link</li>
            <li><strong>Email：</strong> your-email@example.com</li>
            <li><strong>Domain：</strong> shyi655466.com</li>
          </ul>
        </div>
      </section>
    </main>

    <footer class="footer">
      <p>© 2026 Shiyi. Built with Vue 3 + Vite.</p>
    </footer>
  </div>
</template>

<script setup>
</script>