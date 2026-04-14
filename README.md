<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
  <title>Sarankumar | Cyber Sentinel</title>
  <!-- Google Fonts & Font Awesome -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700;14..32,800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <!-- Animate.css for subtle entrances -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: radial-gradient(circle at 10% 20%, #0a0a1a, #03030c);
      font-family: 'Inter', monospace, sans-serif;
      color: #e0e0ff;
      line-height: 1.5;
      scroll-behavior: smooth;
      overflow-x: hidden;
    }

    /* custom neon scrollbar */
    ::-webkit-scrollbar {
      width: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #0f0c29;
    }
    ::-webkit-scrollbar-thumb {
      background: #6c63ff;
      border-radius: 10px;
    }

    /* animated gradient border */
    .glow-card {
      background: rgba(15, 12, 41, 0.6);
      backdrop-filter: blur(4px);
      border: 1px solid rgba(108, 99, 255, 0.3);
      border-radius: 2rem;
      transition: all 0.3s ease;
      box-shadow: 0 10px 25px -5px rgba(0,0,0,0.5);
    }
    .glow-card:hover {
      border-color: #6c63ff;
      box-shadow: 0 0 18px rgba(108, 99, 255, 0.4);
      transform: translateY(-3px);
    }

    .neon-text {
      text-shadow: 0 0 5px #6c63ff, 0 0 10px #3b32b0;
    }

    .btn-neon {
      background: linear-gradient(135deg, #2b2b6e, #14113f);
      border: 1px solid #6c63ff;
      border-radius: 40px;
      padding: 10px 24px;
      font-weight: 600;
      color: white;
      transition: 0.2s;
      display: inline-flex;
      align-items: center;
      gap: 10px;
    }
    .btn-neon:hover {
      background: #6c63ff;
      border-color: #ffffff;
      transform: scale(1.02);
      box-shadow: 0 0 14px #6c63ff;
      color: #fff;
    }

    .skill-badge {
      background: rgba(108, 99, 255, 0.15);
      backdrop-filter: blur(2px);
      border-radius: 40px;
      padding: 6px 16px;
      font-size: 0.85rem;
      font-weight: 500;
      letter-spacing: 0.3px;
      border-left: 2px solid #6c63ff;
      transition: all 0.2s;
    }
    .skill-badge:hover {
      background: #6c63ff30;
      transform: translateX(4px);
    }

    /* header wave animation */
    .wave-bg {
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      overflow: hidden;
      line-height: 0;
      transform: rotate(180deg);
    }
    .wave-bg svg {
      position: relative;
      display: block;
      width: calc(100% + 1.3px);
      height: 80px;
    }

    .glass-panel {
      background: rgba(10, 10, 26, 0.55);
      backdrop-filter: blur(12px);
      border-radius: 2rem;
      border: 1px solid rgba(108, 99, 255, 0.4);
    }

    .glowing-icon {
      transition: 0.2s;
    }
    .glowing-icon:hover {
      text-shadow: 0 0 8px #6c63ff;
      transform: scale(1.05);
    }

    .typewriter {
      overflow: hidden;
      border-right: 2px solid #6c63ff;
      white-space: nowrap;
      width: 0;
      animation: typing 3s steps(32, end) forwards, blink 0.7s step-end infinite;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    @keyframes blink {
      0%, 100% { border-color: #6c63ff; }
      50% { border-color: transparent; }
    }

    .stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1.5rem;
    }

    .project-card {
      background: linear-gradient(145deg, #0e0b24, #08061a);
      border-radius: 1.8rem;
      padding: 1.5rem;
      transition: all 0.25s ease;
      border-bottom: 2px solid #6c63ff50;
    }
    .project-card:hover {
      border-bottom: 2px solid #6c63ff;
      transform: translateY(-5px);
    }

    footer a {
      color: #b9b3ff;
      text-decoration: none;
      transition: 0.2s;
    }
    footer a:hover {
      color: white;
      text-shadow: 0 0 4px #6c63ff;
    }

    @media (max-width: 720px) {
      .typewriter {
        white-space: normal;
        border-right: none;
        animation: none;
        width: 100%;
        text-align: center;
      }
      h1 {
        font-size: 1.9rem;
      }
    }
  </style>
</head>
<body>

  <!-- animated header with capsule style wave -->
  <div style="position: relative; overflow: hidden;">
    <div style="background: linear-gradient(135deg, #0f0c29, #1a1742, #0f0c29); padding: 2.5rem 2rem 4rem;">
      <div class="container" style="max-width: 1280px; margin: 0 auto; text-align: center; position: relative; z-index: 2;">
        <div class="animate__animated animate__fadeInDown">
          <i class="fas fa-shield-haltered" style="font-size: 4rem; color: #6c63ff; filter: drop-shadow(0 0 8px #6c63ff);"></i>
          <h1 style="font-size: 3rem; font-weight: 800; margin-top: 0.5rem;">V. Sarankumar S. Varathaganesh</h1>
          <div class="typewriter" style="font-size: 1.2rem; font-weight: 400; margin: 1rem auto; max-width: fit-content; background: #00000030; padding: 0.5rem 1.2rem; border-radius: 40px;">
            🛡️ Cyber Security Analyst | Red Team | SOC Engineer
          </div>
          <div style="display: flex; flex-wrap: wrap; gap: 12px; justify-content: center; margin-top: 20px;">
            <span class="skill-badge"><i class="fas fa-skull"></i> Ethical Hacker</span>
            <span class="skill-badge"><i class="fas fa-binoculars"></i> Threat Hunter</span>
            <span class="skill-badge"><i class="fas fa-robot"></i> AI Security</span>
            <span class="skill-badge"><i class="fas fa-cloud-upload-alt"></i> Cloud Security</span>
          </div>
        </div>
      </div>
    </div>
    <div class="wave-bg">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path fill="#03030c" fill-opacity="1" d="M0,224L48,208C96,192,192,160,288,165.3C384,171,480,213,576,218.7C672,224,768,192,864,176C960,160,1056,160,1152,170.7C1248,181,1344,203,1392,213.3L1440,224L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path>
      </svg>
    </div>
  </div>

  <div class="container" style="max-width: 1280px; margin: 2rem auto; padding: 0 1.5rem;">
    
    <!-- ABOUT ME section with glassmorphism -->
    <div class="glass-panel p-6 animate__animated animate__fadeInUp" style="padding: 1.8rem; margin-bottom: 2.5rem;">
      <div style="display: flex; flex-wrap: wrap; align-items: center; gap: 20px;">
        <div style="flex:1;">
          <h2 style="font-size: 1.9rem; font-weight: 700; border-left: 5px solid #6c63ff; padding-left: 18px;"><i class="fas fa-user-secret"></i> ABOUT ME</h2>
          <p style="margin-top: 1rem; font-size: 1rem; line-height: 1.6;">🎯 Cybersecurity Engineering Student (B.Tech CSIT) <br>
          🔐 Hands-on in SOC, SIEM, Red Team & Blue Team labs <br>
          ⚔️ Active Directory attack & defense simulations <br>
          ☁️ Cloud Security (AWS IAM, EC2, RDS) <br>
          🧩 Passionate about CTFs, Hackathons, Threat Intelligence <br>
          ⚡ <span class="neon-text">"Think like a hacker, defend like a warrior"</span></p>
        </div>
        <div style="flex-shrink:0;">
          <i class="fas fa-terminal" style="font-size: 5rem; opacity: 0.7; color: #6c63ff;"></i>
        </div>
      </div>
    </div>

    <!-- TECH STACK with icons & animated -->
    <h2 class="animate__animated animate__fadeInRight" style="font-size: 1.8rem; margin-bottom: 1rem; display: flex; align-items: center; gap: 12px;"><i class="fas fa-microchip"></i> TECH STACK <span style="font-size: 0.8rem; background: #6c63ff40; padding: 2px 12px; border-radius: 40px;">arsenal ready</span></h2>
    <div class="stats-grid" style="margin-bottom: 2rem;">
      <div class="glow-card" style="padding: 1.2rem;">
        <h3><i class="fab fa-python"></i> Programming</h3>
        <div style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 12px;">
          <span class="skill-badge">Python</span><span class="skill-badge">Java</span><span class="skill-badge">JavaScript</span><span class="skill-badge">Bash</span>
        </div>
      </div>
      <div class="glow-card" style="padding: 1.2rem;">
        <h3><i class="fas fa-shield-virus"></i> Cyber Security Tools</h3>
        <div style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 12px;">
          <span class="skill-badge">Wazuh</span><span class="skill-badge">ELK Stack</span><span class="skill-badge">Zabbix</span><span class="skill-badge">AlienVault</span>
        </div>
      </div>
      <div class="glow-card" style="padding: 1.2rem;">
        <h3><i class="fas fa-server"></i> Systems & Cloud</h3>
        <div style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 12px;">
          <span class="skill-badge">Linux</span><span class="skill-badge">Active Directory</span><span class="skill-badge">AWS</span><span class="skill-badge">Docker</span>
        </div>
      </div>
    </div>

    <!-- FEATURED PROJECTS (with more style) -->
    <h2 class="animate__animated animate__fadeInRight" style="font-size: 1.8rem; margin: 2rem 0 1rem;"><i class="fas fa-rocket"></i> FEATURED PROJECTS</h2>
    <div class="stats-grid" style="margin-bottom: 2rem;">
      <div class="project-card">
        <i class="fas fa-user-ninja" style="font-size: 2.3rem; color: #6c63ff;"></i>
        <h3 style="margin: 12px 0 6px;">🕶️ Anonymous Red Team Env</h3>
        <p>Isolated hacking lab using Qubes OS + sys-whonix. Simulated attack/defense + SIEM monitoring integration.</p>
        <div style="margin-top: 12px;"><span class="skill-badge">Red Teaming</span><span class="skill-badge">SIEM</span></div>
      </div>
      <div class="project-card">
        <i class="fas fa-dna" style="font-size: 2.3rem; color: #6c63ff;"></i>
        <h3 style="margin: 12px 0 6px;">🧬 AI Chronic Disease System</h3>
        <p>ML-based prediction for early disease detection. High accuracy and real-time data analysis.</p>
        <div><span class="skill-badge">Machine Learning</span><span class="skill-badge">Python</span></div>
      </div>
      <div class="project-card">
        <i class="fas fa-eye" style="font-size: 2.3rem; color: #6c63ff;"></i>
        <h3 style="margin: 12px 0 6px;">🛡️ AI Security Scanner</h3>
        <p>Real-time threat dashboard monitoring network + processes using anomaly detection AI.</p>
        <div><span class="skill-badge">AI</span><span class="skill-badge">Network Sec</span></div>
      </div>
    </div>

    <!-- GITHUB STATS (elegant cards) -->
    <div class="stats-grid" style="margin: 2rem 0;">
      <div class="glass-panel" style="padding: 1.2rem; text-align: center;">
        <i class="fab fa-github" style="font-size: 2rem;"></i>
        <h3>GitHub Stats</h3>
        <img src="https://github-readme-stats.vercel.app/api?username=sarankumar-2209&show_icons=true&theme=radical&bg_color=0d0b1a&title_color=6c63ff&icon_color=6c63ff" width="100%" style="border-radius: 18px;" alt="stats">
      </div>
      <div class="glass-panel" style="padding: 1.2rem; text-align: center;">
        <i class="fas fa-chart-line"></i>
        <h3>Top Languages</h3>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sarankumar-2209&layout=compact&theme=radical&bg_color=0d0b1a&title_color=6c63ff" width="100%" style="border-radius: 18px;" alt="top langs">
      </div>
    </div>

    <!-- Activity graph + custom style -->
    <div class="glow-card" style="padding: 1rem; margin: 2rem 0; text-align: center;">
      <h3><i class="fas fa-fire"></i> ACTIVITY GRAPH</h3>
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=sarankumar-2209&theme=react-dark&bg_color=0a0a1a&color=6c63ff&line=6c63ff&point=ffffff&area=true" width="100%" style="border-radius: 20px; margin-top: 12px;" alt="activity graph">
    </div>

    <!-- snake contribution gif (official) using platane/snk but with fallback svg - we embed remote image -->
    <div class="glass-panel" style="padding: 1.5rem; text-align: center; margin: 2rem 0;">
      <h3><i class="fas fa-gamepad"></i> SNAKE CONTRIBUTION GRAPH</h3>
      <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" onerror="this.src='https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg'" alt="snake animation" style="max-width: 100%; background: #00000030; border-radius: 28px; margin-top: 10px;">
      <p style="font-size: 0.75rem; margin-top: 8px;">🐍 contribution snake animation (lighthearted)</p>
    </div>

    <!-- TROPHIES with github profile trophies -->
    <div class="glow-card" style="padding: 1rem; margin: 2rem 0; text-align: center;">
      <h3><i class="fas fa-trophy"></i> ACHIEVEMENT TROPHIES</h3>
      <img src="https://github-profile-trophy.vercel.app/?username=sarankumar-2209&theme=radical&no-frame=true&column=4&margin-w=12" width="100%" style="border-radius: 20px;" alt="trophies">
    </div>

    <!-- CONNECT WITH ME + socials elegant footer -->
    <div style="background: rgba(0,0,0,0.4); border-radius: 2rem; padding: 2rem; margin: 2rem 0; text-align: center; backdrop-filter: blur(8px);">
      <h2><i class="fas fa-address-card"></i> CONNECT WITH ME</h2>
      <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 2rem; margin-top: 1.5rem;">
        <a href="mailto:saran2209kumar@gmail.com" class="btn-neon" style="text-decoration: none;"><i class="fas fa-envelope"></i> saran2209kumar@gmail.com</a>
        <a href="#" class="btn-neon" style="text-decoration: none;"><i class="fab fa-linkedin"></i> LinkedIn: Saran Kumar</a>
        <a href="https://github.com/sarankumar-2209" target="_blank" class="btn-neon" style="text-decoration: none;"><i class="fab fa-github"></i> github.com/sarankumar-2209</a>
      </div>
      <div style="margin-top: 2rem; font-size: 0.85rem; opacity: 0.8;">
        <i class="fas fa-shield-alt"></i> "Think like a hacker, defend like a warrior"
      </div>
    </div>
    
    <!-- cool terminal quote -->
    <div style="text-align: center; padding: 1rem; font-family: monospace; background: #0b091b; border-radius: 20px; margin-bottom: 1rem;">
      <i class="fas fa-terminal"></i> root@cyber:~# <span id="dynamic-text"></span><span style="animation: blink 1s infinite;">|</span>
    </div>
  </div>

  <footer style="text-align: center; padding: 1.5rem; border-top: 1px solid #2a275a; margin-top: 1rem;">
    <p>© 2025 Sarankumar — Cyber Security Arsenal | <i class="fas fa-skull-crossbones"></i> Red Team mindset, Blue Team discipline</p>
    <p style="font-size: 0.7rem;">Built with neon & passion — always evolving</p>
  </footer>

  <script>
    // dynamic hacker-style text rotation
    const messages = [
      "sudo nmap -sS target.com",
      "Analyzing SIEM alerts...",
      "Active Directory hardening in progress",
      "Threat hunting mode engaged",
      "python3 ai_scanner.py --deep"
    ];
    let idx = 0;
    const dynEl = document.getElementById("dynamic-text");
    function updateTerminalText() {
      if(dynEl) {
        dynEl.textContent = messages[idx % messages.length];
        idx++;
      }
    }
    updateTerminalText();
    setInterval(updateTerminalText, 3200);

    // add smooth hover effects on stat images (just for extra feel)
    const imgs = document.querySelectorAll('.glass-panel img, .glow-card img');
    imgs.forEach(img => {
      img.style.transition = "transform 0.2s ease, filter 0.2s";
      img.addEventListener('mouseenter', () => {
        img.style.transform = "scale(1.01)";
        img.style.filter = "drop-shadow(0 0 6px #6c63ff)";
      });
      img.addEventListener('mouseleave', () => {
        img.style.transform = "scale(1)";
        img.style.filter = "none";
      });
    });
    
    // animated counters for fun? not necessary, but adds a little glimmer
    const style = document.createElement('style');
    style.innerHTML = `@keyframes pulseBorder { 0% { border-color: #6c63ff40; } 100% { border-color: #6c63ff; } }`;
    document.head.appendChild(style);
    
    // small console easter egg
    console.log("%c🛡️ Welcome to Sarankumar's cyber realm | Red Team ready", "color: #6c63ff; font-size: 16px; font-weight: bold;");
  </script>
</body>
</html>
