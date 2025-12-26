<h1 align="center">Hey there! 👋</h1>
<p align="center"><strong>I'm Rizza — Backend Developer & Student</strong></p>

<p align="center">
  I specialize in:
</p>

<ul style="display:inline-block; text-align:left; list-style:none; padding:0; margin:16px 0;">
  <li>• Discord & Telegram bots</li>
  <li>• APIs & backend services</li>
  <li>• Automation & personal projects</li>
</ul>

<p align="center">
  <a href="https://t.me/unbrokenflex">
    <img src="https://img.shields.io/badge/Telegram-@unbrokenflex-blue?style=for-the-badge&logo=telegram" alt="Telegram">
  </a>
</p>

<style>
  /* GitHub полностью поддерживает эти свойства (2025 год — всё стабильно работает) */
  :root {
    --bg: #0d1117;                 /* тёмный фон GitHub */
    --glass: rgba(30, 35, 50, 0.55);
    --glass-hover: rgba(40, 45, 70, 0.7);
    --border: rgba(100, 110, 255, 0.25);
    --accent: #8b6dff;
    --text: #e6edf3;
    --text-secondary: #adbac7;
    --shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
  }

  .glass-section {
    background: var(--glass);
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    border-radius: 20px;
    border: 1px solid rgba(255, 255, 255, 0.1);
    padding: 28px;
    margin: 32px 0;
    transition: all 0.6s cubic-bezier(0.16, 1, 0.3, 1);
    box-shadow: var(--shadow);
    overflow: hidden;
    position: relative;
  }

  .glass-section::before {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, rgba(139, 109, 255, 0.05), transparent 50%);
    opacity: 0;
    transition: opacity 0.6s ease;
    pointer-events: none;
  }

  .glass-section:hover {
    transform: translateY(-10px);
    background: var(--glass-hover);
    border-color: var(--border);
    box-shadow: 0 24px 60px rgba(139, 109, 255, 0.25);
  }

  .glass-section:hover::before {
    opacity: 1;
  }

  .tech-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 14px;
    justify-content: center;
    margin: 24px 0;
  }

  .tech-badge {
    transition: all 0.45s cubic-bezier(0.25, 0.8, 0.25, 1);
    filter: brightness(1) saturate(1);
  }

  .tech-badge:hover {
    transform: translateY(-8px) scale(1.1);
    filter: brightness(1.3) saturate(1.4) drop-shadow(0 12px 24px rgba(139, 109, 255, 0.4));
  }

  .project-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 28px;
    justify-content: center;
    margin-top: 20px;
  }

  .project-card {
    width: 340px;
    background: var(--glass);
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    border-radius: 18px;
    border: 1px solid rgba(255, 255, 255, 0.08);
    padding: 26px;
    text-align: center;
    transition: all 0.7s cubic-bezier(0.16, 1, 0.3, 1);
    box-shadow: var(--shadow);
  }

  .project-card:hover {
    transform: translateY(-18px) scale(1.03);
    background: var(--glass-hover);
    border-color: var(--accent);
    box-shadow: 0 32px 70px rgba(139, 109, 255, 0.35);
  }

  .project-badge {
    transition: all 0.5s ease;
  }

  .project-badge:hover {
    transform: scale(1.15);
    filter: drop-shadow(0 0 20px rgba(0, 126, 198, 0.8));
  }

  .floating-gif {
    transition: all 0.6s ease;
    filter: drop-shadow(0 0 30px rgba(139, 109, 255, 0.3));
  }

  .floating-gif:hover {
    transform: scale(1.15) rotate(5deg);
  }

  h2 {
    margin-top: 0;
    color: var(--text);
    position: relative;
    display: inline-block;
  }

  h2::after {
    content: '';
    position: absolute;
    bottom: -8px;
    left: 50%;
    width: 60px;
    height: 3px;
    background: var(--accent);
    border-radius: 2px;
    transform: translateX(-50%);
    transition: width 0.4s ease;
  }

  .glass-section:hover h2::after {
    width: 100px;
  }
</style>

<div class="glass-section">
  <h2 align="center">⚡ Technologies</h2>
  <div class="tech-grid">
    <img class="tech-badge" src="https://img.shields.io/badge/-Python-FFD43B?style=for-the-badge&logo=Python&logoColor=blue" alt="Python">
    <img class="tech-badge" src="https://img.shields.io/badge/-Rust-DEA584?style=for-the-badge&logo=rust&logoColor=black" alt="Rust">
    <img class="tech-badge" src="https://img.shields.io/badge/-C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C">
    <img class="tech-badge" src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img class="tech-badge" src="https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
    <img class="tech-badge" src="https://img.shields.io/badge/-MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
    <img class="tech-badge" src="https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
    <img class="tech-badge" src="https://img.shields.io/badge/-Google_Cloud-F4B400?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Google Cloud">
    <img class="tech-badge" src="https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
    <img class="tech-badge" src="https://img.shields.io/badge/-GitHub-6e5494?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
    <img class="tech-badge" src="https://img.shields.io/badge/-ArchLinux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white" alt="ArchLinux">
    <img class="tech-badge" src="https://img.shields.io/badge/-Hyprland-F72585?style=for-the-badge&logoColor=white" alt="Hyprland">
  </div>
</div>

<div class="glass-section">
  <h2 align="center">🚀 Currently Working On</h2>
  <ul style="text-align:left; max-width:600px; margin:20px auto; color:var(--text-secondary); line-height:1.8;">
    <li>Discord & Telegram bots</li>
    <li>Backend APIs & automation services</li>
    <li>Personal projects exploring Rust & C</li>
  </ul>
  <p align="center" style="margin-top:40px;">
    <img class="floating-gif" src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="90" alt="Coding gif"/>
  </p>
</div>

<div class="glass-section">
  <h2 align="center">🛠️ My Projects (Closed Source)</h2>
  <div class="project-grid">
    <div class="project-card">
      <h3>Spylens</h3>
      <p style="color:var(--text-secondary);">Telegram bot for tracking deleted/edited messages, photos, voice & video notes, and saving self-destructing media</p>
      <a href="https://t.me/spylens">
        <img class="project-badge" src="https://img.shields.io/badge/Telegram-Open-blue?style=for-the-badge&logo=telegram" alt="Spylens">
      </a>
    </div>

    <div class="project-card">
      <h3>ClassFlow</h3>
      <p style="color:var(--text-secondary);">Telegram bot for students of all branches & faculties of MGUTU to check up-to-date class schedules</p>
      <a href="https://t.me/classflowdev">
        <img class="project-badge" src="https://img.shields.io/badge/Telegram-Open-blue?style=for-the-badge&logo=telegram" alt="ClassFlow">
      </a>
    </div>

    <div class="project-card">
      <h3>Toolbox (Tester)</h3>
      <p style="color:var(--text-secondary);">Universal Telegram assistant: AI answers, image generation, file processing, and more</p>
      <a href="https://t.me/toolbox">
        <img class="project-badge" src="https://img.shields.io/badge/Telegram-Open-blue?style=for-the-badge&logo=telegram" alt="Toolbox">
      </a>
    </div>
  </div>
</div>
