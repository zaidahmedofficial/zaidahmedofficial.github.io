<div class="profile-container">
  <div class="terminal">
    <div class="terminal-header">
      <span class="dot red"></span>
      <span class="dot yellow"></span>
      <span class="dot green"></span>
    </div>
    <div class="terminal-body">
      <div class="typing-line">
        <span class="prompt">zaid@github</span>
        <span class="cursor-blink">|</span>
      </div>
      <p class="status-line">
        <span class="arrow">→</span> Crafting responsive interfaces since 2020
      </p>
      <div class="skills-container">
        <div class="skill-tag html">HTML</div>
        <div class="skill-tag css">CSS</div>
        <div class="skill-tag tailwind">TailwindCSS</div>
        <div class="skill-tag js">JS</div>
        <div class="skill-tag react">ReactJS</div>
        <div class="skill-tag ts">TS</div>
      </div>
      <p class="note">
        "Code is poetry, but sometimes it needs a better editor"
      </p>
    </div>
  </div>
</div>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    background: #0d1117;
    color: #c9d1d9;
    font-family: 'Courier New', monospace;
    padding: 2rem;
  }

  .profile-container {
    max-width: 600px;
    margin: 0 auto;
  }

  .terminal {
    background: #161b22;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
    animation: fadeIn 1s ease-in;
  }

  .terminal-header {
    background: #21262d;
    padding: 0.5rem 1rem;
    display: flex;
    gap: 0.5rem;
  }

  .dot {
    width: 12px;
    height: 12px;
    border-radius: 50%;
  }

  .red { background: #ff5f56; }
  .yellow { background: #ffbd2e; }
  .green { background: #27c93f; }

  .terminal-body {
    padding: 1.5rem;
    line-height: 1.6;
  }

  .typing-line {
    margin-bottom: 1rem;
  }

  .prompt {
    color: #7ee787;
    margin-right: 0.5rem;
  }

  .cursor-blink {
    animation: blink 1s infinite;
  }

  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }

  .status-line {
    margin: 0.5rem 0;
    color: #8b949e;
  }

  .arrow {
    color: #58a6ff;
    margin-right: 0.5rem;
  }

  .skills-container {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin: 1rem 0;
  }

  .skill-tag {
    padding: 0.3rem 0.7rem;
    border-radius: 4px;
    font-size: 0.85rem;
    font-weight: bold;
    animation: slideIn 0.5s ease-out forwards;
    opacity: 0;
    transform: translateY(10px);
  }

  .html {
    background: #e34c26;
    color: white;
    animation-delay: 1.5s;
  }

  .css {
    background: #264de4;
    color: white;
    animation-delay: 1.8s;
  }

  .tailwind {
    background: #06b6d4;
    color: white;
    animation-delay: 2.1s;
  }

  .js {
    background: #f7df1e;
    color: black;
    animation-delay: 2.4s;
  }

  .react {
    background: #61dafb;
    color: black;
    animation-delay: 2.7s;
  }

  .ts {
    background: #3178c6;
    color: white;
    animation-delay: 3s;
  }

  @keyframes slideIn {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  .note {
    margin-top: 1rem;
    color: #8b949e;
    font-style: italic;
    animation: fadeIn 1s ease-in 3.5s;
    opacity: 0;
  }

  @keyframes fadeIn {
    to { opacity: 1; }
  }
</style>
