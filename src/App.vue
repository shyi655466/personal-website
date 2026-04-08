<template>
  <div class="page">
    <header class="navbar">
      <a class="brand" href="#top">Shiyi</a>
      <nav class="nav-links" aria-label="主导航">
        <a href="#about">关于</a>
        <a href="#skills">技能</a>
        <a href="#projects">项目</a>
        <a href="#contact">联系</a>
      </nav>
    </header>

    <main id="top">
      <section class="hero section" aria-labelledby="hero-title">
        <div class="hero-content">
          <p class="eyebrow">Programmer / Learner / Builder</p>
          <h1 id="hero-title">你好，我是拾忆</h1>
          <p class="hero-desc">
            持续学习全栈开发与 AI 工具实践，把阶段性成长沉淀成可展示、可复盘、可迭代的个人作品。
          </p>
          <div class="hero-actions" aria-label="快捷入口">
            <a class="btn primary" href="#projects">查看项目</a>
            <a class="btn secondary" href="#contact">联系我</a>
          </div>
        </div>
      </section>

      <section class="stats section" aria-label="当前状态">
        <div class="stat-item">
          <span>01</span>
          <strong>长期迭代</strong>
          <p>个人网站与项目作品集</p>
        </div>
        <div class="stat-item">
          <span>Vue 3</span>
          <strong>当前主线</strong>
          <p>组件化开发与前端工程化</p>
        </div>
        <div class="stat-item">
          <span>AI</span>
          <strong>关注方向</strong>
          <p>工具链效率与智能应用实践</p>
        </div>
      </section>

      <section id="about" class="section about-section">
        <div class="section-header">
          <p class="eyebrow">About</p>
          <h2>关于我</h2>
          <p>
            我正在系统学习前端开发、后端基础与项目部署，把学习内容转化为实际作品，并持续整理自己的技术路线。
          </p>
        </div>

        <div class="about-layout">
          <article class="panel intro-panel">
            <h3>成长中的开发者</h3>
            <p>
              目前聚焦 Vue 3、Vite、JavaScript、Python 与 AI 相关知识。这个站点会作为长期项目，
              记录学习路径、项目成果和后续技术输出。
            </p>
          </article>

          <div class="timeline">
            <article class="timeline-item">
              <span>现在</span>
              <h3>完善个人主页</h3>
              <p>整理个人介绍、技能栈、项目案例与联系方式，形成清晰的作品展示入口。</p>
            </article>
            <article class="timeline-item">
              <span>下一步</span>
              <h3>沉淀项目详情</h3>
              <p>补充项目背景、技术方案、实现过程与部署记录，让每个项目更容易复盘。</p>
            </article>
            <article class="timeline-item">
              <span>长期</span>
              <h3>持续技术输出</h3>
              <p>逐步加入博客、学习笔记和实验记录，建立稳定的个人技术档案。</p>
            </article>
          </div>
        </div>
      </section>

      <section id="skills" class="section">
        <div class="section-header">
          <p class="eyebrow">Skills</p>
          <h2>技能栈</h2>
          <p>以能落地项目为目标，围绕界面实现、工程协作、后端基础和智能工具持续补齐能力。</p>
        </div>

        <div class="skills-grid">
          <article class="card">
            <span class="card-index">01</span>
            <h3>前端开发</h3>
            <p>HTML、CSS、JavaScript、Vue 3、Vite，关注响应式布局与组件化实践。</p>
          </article>
          <article class="card">
            <span class="card-index">02</span>
            <h3>编程语言</h3>
            <p>Python、JavaScript，用于脚本处理、页面交互、数据处理与项目原型验证。</p>
          </article>
          <article class="card">
            <span class="card-index">03</span>
            <h3>工具链</h3>
            <p>Git、GitHub、VS Code、Vercel，围绕开发、版本管理和部署形成基础流程。</p>
          </article>
          <article class="card">
            <span class="card-index">04</span>
            <h3>正在学习</h3>
            <p>前端工程化、接口对接、后端基础、AI 辅助开发与个人项目持续交付。</p>
          </article>
        </div>
      </section>

      <section id="projects" class="section">
        <div class="section-header">
          <p class="eyebrow">Projects</p>
          <h2>项目展示</h2>
          <p>从真实需求和学习任务出发，持续打磨结构、交互、工程组织和部署流程。</p>
        </div>

        <div class="projects-grid">
          <article class="project-card">
            <div class="project-meta">
              <span>Vue 3 / Vite</span>
              <span>持续迭代</span>
            </div>
            <h3>个人主页网站</h3>
            <p>
              面向个人品牌和作品展示的长期项目，持续完善页面结构、内容组织、视觉层级与部署流程。
            </p>
          </article>

          <article class="project-card">
            <div class="project-meta">
              <span>Vue / Element Plus</span>
              <span>前端实践</span>
            </div>
            <h3>HRD 前端项目</h3>
            <p>
              围绕样本管理、分析流程与结果展示进行界面设计和组件拆分，练习前后端对接思路。
            </p>
          </article>

          <article class="project-card">
            <div class="project-meta">
              <span>Python / YOLO / OCR</span>
              <span>视觉识别</span>
            </div>
            <h3>车牌识别项目</h3>
            <p>
              基于计算机视觉与文本识别流程进行工程练习，积累模型调用、数据处理和结果展示经验。
            </p>
          </article>
        </div>
      </section>

      <section id="contact" class="section contact-section">
        <div class="contact-card">
          <div>
            <p class="eyebrow">Contact</p>
            <h2>欢迎交流</h2>
            <p>
              如果你想了解我的项目、交流学习路线，或一起讨论前端、Python 与 AI 工具实践，可以通过下面的方式找到我。
            </p>
          </div>
          <div class="contact-links">
            <a href="https://github.com/shyi655466" target="_blank" rel="noreferrer">GitHub</a>
            <a href="mailto:yi655466@gmail.com">Email</a>
            <a href="https://shyi655466.com" target="_blank" rel="noreferrer">Domain</a>
          </div>
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
