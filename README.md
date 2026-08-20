<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Tech-Lab presents Study4U — learn, build and grow." />
  <meta name="theme-color" content="#10131f" />
  <title>Tech-Lab | Learn. Build. Grow.</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="background-grid"></div>

  <main class="hero">
    <nav class="navbar">
      <a class="brand" href="#" aria-label="Tech-Lab home">
        <span class="brand-mark">T</span>
        <span>TECH<span>-LAB</span></span>
      </a>

      <div class="nav-actions">
        <a href="#features" class="nav-link">Features</a>
        <a href="#projects" class="nav-link">Projects</a>
        <a href="#study4u" class="nav-link">Study4U</a>
        <button id="themeToggle" class="theme-toggle" type="button" aria-label="Toggle theme">☾</button>
      </div>
    </nav>

    <section class="content">
      <div class="badge">✦ Technology for a brighter future</div>

      <h1>
        Learn.
        <span>Build.</span>
        Grow.
      </h1>

      <p class="intro">
        Tech-Lab helps curious minds discover better ways to learn, create
        powerful projects, and prepare for the future.
      </p>

      <div class="hero-buttons">
        <a class="action-button" href="#study4u">Explore Study4U <span>→</span></a>
        <a class="secondary-button" href="#projects">View projects</a>
      </div>

      <div class="clock-card" id="clock">
        <p class="clock-label">YOUR LOCAL TIME</p>
        <p id="currentTime" class="time" aria-live="polite">Loading...</p>
        <p id="currentDate" class="date"></p>
      </div>

      <p id="message" class="message" aria-live="polite"></p>
    </section>

    <section class="stats reveal" aria-label="Tech-Lab statistics">
      <div class="stat">
        <strong data-count="100">0</strong><span>+</span>
        <p>Learning resources</p>
      </div>
      <div class="stat">
        <strong data-count="24">0</strong><span>/7</span>
        <p>Learn anytime</p>
      </div>
      <div class="stat">
        <strong data-count="100">0</strong><span>%</span>
        <p>Future focused</p>
      </div>
    </section>

    <section class="features reveal" id="features">
      <div class="section-heading">
        <span class="eyebrow">WHY TECH-LAB</span>
        <h2>Everything you need to move forward.</h2>
      </div>

      <div class="feature-grid">
        <article class="feature-card">
          <div class="feature-icon">⌘</div>
          <h3>Learn smarter</h3>
          <p>Clear resources and simple explanations designed for effective learning.</p>
        </article>

        <article class="feature-card">
          <div class="feature-icon">⚡</div>
          <h3>Build skills</h3>
          <p>Turn ideas into practical projects and develop skills that matter.</p>
        </article>

        <article class="feature-card">
          <div class="feature-icon">🚀</div>
          <h3>Grow together</h3>
          <p>Stay motivated, explore new possibilities, and make progress every day.</p>
        </article>
      </div>
    </section>

    <section class="projects reveal" id="projects">
      <div class="section-heading">
        <span class="eyebrow">OUR PROJECTS</span>
        <h2>Ideas made real by Tech-Lab.</h2>
      </div>

      <div class="project-grid">
        <article class="project-card project-study">
          <div class="project-icon">📚</div>
          <span class="project-label">LEARNING PLATFORM</span>
          <h3>Study4U</h3>
          <p>
            Discover useful learning resources and take your next step toward
            a brighter future.
          </p>
          <div class="project-actions">
            <a class="project-button" href="https://AJ-8A.github.io/study4u" target="_blank" rel="noopener noreferrer">
              Visit Study4U ↗
            </a>
          </div>
        </article>
      </div>
    </section>

    <section class="tech-ad reveal" id="study4u" aria-label="Tech-Lab Study4U advertisement">
      <div class="ad-glow"></div>
      <div class="floating-orb orb-one"></div>
      <div class="floating-orb orb-two"></div>

      <div class="ad-content">
        <div class="ad-logo">
          <span class="ad-logo-mark">T</span>
          <span>TECH-LAB</span>
        </div>

        <span class="ad-tag">TECH-LAB PRESENTS</span>
        <h2>Your next chapter starts with <strong>Study4U.</strong></h2>
        <p>
          Explore your Study4U learning experience, discover useful resources,
          and take the next step toward your future.
        </p>

        <a class="ad-button" href="https://AJ-8A.github.io/study4u" target="_blank" rel="noopener noreferrer">
          Visit Study4U <span>↗</span>
        </a>
      </div>

      <div class="ad-preview">
        <div class="preview-bar">
          <span></span><span></span><span></span>
        </div>
        <iframe
          src="https://AJ-8A.github.io/study4u"
          title="Study4U by Tech-Lab"
          loading="lazy"
        ></iframe>
        <a class="preview-link" href="https://AJ-8A.github.io/study4u" target="_blank" rel="noopener noreferrer">
          Open the full Study4U website →
        </a>
      </div>
    </section>

    <section class="final-cta reveal">
      <span class="eyebrow">READY TO START?</span>
      <h2>Make your ideas useful.</h2>
      <p>Learn something new today and let your future self thank you.</p>
      <a class="action-button" href="https://AJ-8A.github.io/study4u" target="_blank" rel="noopener noreferrer">
        Start learning <span>→</span>
      </a>
    </section>

    <footer>
      <p>© 2026 <strong>Tech-Lab</strong> · Designed to inspire learning <span>♥</span></p>

      <div class="social-links">
        <a href="https://github.com/AJ-8A" target="_blank" rel="noopener noreferrer">
          GitHub
        </a>
        <a href="https://github.com/ajofficial777" target="_blank" rel="noopener noreferrer">
          AJ Official GitHub
        </a>
      </div>
    </footer>
  </main>

  <script src="script.js"></script>
</body>
</html>
