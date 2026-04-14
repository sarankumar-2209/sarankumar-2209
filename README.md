<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarankumar · Cyber Security Analyst</title>
    <!-- Font Awesome 6 (free) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <!-- Google Fonts: JetBrains Mono + Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700;14..32,800&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: radial-gradient(circle at 20% 30%, #0a0a1a, #02010a);
            font-family: 'Inter', 'JetBrains Mono', monospace, sans-serif;
            color: #eef2ff;
            line-height: 1.5;
            padding: 2rem 1.5rem;
        }

        /* main container with max width for GitHub readme style */
        .github-container {
            max-width: 1100px;
            margin: 0 auto;
            background: rgba(8, 6, 20, 0.65);
            backdrop-filter: blur(2px);
            border-radius: 2.5rem;
            padding: 2rem 2rem 2rem 2rem;
            box-shadow: 0 25px 40px -12px rgba(0, 0, 0, 0.6), 0 0 0 1px rgba(108, 99, 255, 0.15);
        }

        /* custom glows & borders */
        .glow-text {
            text-shadow: 0 0 6px #6c63ff, 0 0 12px #3b2f9e;
        }
        .badge {
            background: rgba(108, 99, 255, 0.12);
            border-radius: 40px;
            padding: 6px 16px;
            font-size: 0.8rem;
            font-weight: 500;
            font-family: 'JetBrains Mono', monospace;
            backdrop-filter: blur(2px);
            border: 1px solid rgba(108, 99, 255, 0.3);
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }
        .badge:hover {
            background: rgba(108, 99, 255, 0.25);
            border-color: #6c63ff;
            transform: translateY(-2px);
        }

        .tech-pill {
            background: #0f0d2c;
            border-left: 3px solid #6c63ff;
            padding: 0.3rem 1rem;
            border-radius: 30px;
            font-size: 0.85rem;
            font-weight: 500;
        }

        .project-card {
            background: linear-gradient(135deg, #0c0a1f, #060514);
            border-radius: 1.5rem;
            padding: 1.3rem;
            transition: all 0.25s;
            border-bottom: 2px solid #2c286b;
            height: 100%;
        }
        .project-card:hover {
            border-bottom-color: #6c63ff;
            transform: translateY(-5px);
            box-shadow: 0 15px 25px -10px rgba(0,0,0,0.5);
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.6rem;
            margin: 2rem 0;
        }

        .glass-stats {
            background: rgba(12, 10, 30, 0.6);
            backdrop-filter: blur(8px);
            border-radius: 1.8rem;
            padding: 1.2rem;
            text-align: center;
            border: 1px solid rgba(108, 99, 255, 0.2);
        }

        hr {
            border: none;
            height: 1px;
            background: linear-gradient(90deg, transparent, #6c63ff, #a55cff, transparent);
            margin: 1.8rem 0;
        }

        .social-icon {
            background: #13112e;
            border-radius: 60px;
            padding: 10px 20px;
            transition: 0.2s;
            display: inline-flex;
            align-items: center;
            gap: 12px;
            text-decoration: none;
            color: #eef2ff;
            font-weight: 500;
            border: 1px solid #2a2760;
        }
        .social-icon:hover {
            background: #6c63ff;
            color: white;
            border-color: white;
            transform: scale(1.02);
        }

        .typewriter-terminal {
            font-family: 'JetBrains Mono', monospace;
            background: #03000f;
            padding: 0.8rem 1.5rem;
            border-radius: 2rem;
            display: inline-block;
            border-left: 4px solid #6c63ff;
        }

        .footer-quote {
            font-size: 0.9rem;
            text-align: center;
            letter-spacing: 0.5px;
        }

        @media (max-width: 680px) {
            .github-container {
                padding: 1.5rem;
            }
            h1 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
<div class="github-container">
    
    <!-- HEADER SECTION with waving & animated vibe -->
    <div style="text-align: center; margin-bottom: 1.8rem;">
        <!-- simulated header capsule animation (github friendly) -->
        <div style="background: linear-gradient(130deg, #0f0c29, #1f1b4b); padding: 1.2rem; border-radius: 3rem; margin-bottom: 1.2rem;">
            <i class="fas fa-shield-haltered" style="font-size: 3rem; color: #6c63ff; filter: drop-shadow(0 0 6px #6c63ff);"></i>
            <h1 style="font-size: 2.5rem; font-weight: 800; margin: 0.5rem 0 0.2rem;">V. Sarankumar S. Varathaganesh</h1>
            <div class="typewriter-terminal" style="margin: 0.8rem auto; width: fit-content;">
                <i class="fas fa-terminal"></i> cyber@sec:~$ whoami — 🛡️ Red Team | SOC | Threat Hunter
            </div>
            <div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 20px;">
                <span class="badge"><i class="fas fa-skull"></i> Ethical Hacker</span>
                <span class="badge"><i class="fas fa-eye"></i> Threat Hunter</span>
                <span class="badge"><i class="fas fa-shield-virus"></i> SOC Engineer</span>
                <span class="badge"><i class="fas fa-cloud-upload-alt"></i> Cloud Security</span>
            </div>
        </div>
    </div>

    <!-- ABOUT ME (clean and punchy) -->
    <div style="display: flex; flex-wrap: wrap; gap: 2rem; justify-content: space-between; margin: 2rem 0;">
        <div style="flex: 2;">
            <h2 style="font-size: 1.8rem; border-left: 5px solid #6c63ff; padding-left: 18px;"><i class="fas fa-user-astronaut"></i> ABOUT ME</h2>
            <p style="margin-top: 1rem; line-height: 1.6;">🎯 Cybersecurity Engineering Student (B.Tech CSIT) <br>
            🔐 Hands-on in SOC, SIEM, Red Team & Blue Team labs <br>
            ⚔️ Active Directory attack & defense simulations <br>
            ☁️ Cloud Security (AWS IAM, EC2, RDS) <br>
            🧩 Passionate about CTFs, Hackathons, Threat Intelligence <br>
            ⚡ <span class="glow-text">"Think like a hacker, defend like a warrior"</span></p>
        </div>
        <div style="flex: 1; text-align: center; background: rgba(0,0,0,0.3); border-radius: 2rem; padding: 1rem;">
            <i class="fas fa-terminal" style="font-size: 4rem; opacity: 0.8; color: #6c63ff;"></i>
            <p style="font-family: monospace; margin-top: 8px;"># root@cybersec ~</p>
        </div>
    </div>

    <hr>

    <!-- TECH STACK with visual icons and categories -->
    <h2 style="display: flex; align-items: center; gap: 12px; margin-bottom: 1.2rem;"><i class="fas fa-microchip"></i> TECH STACK & TOOLS</h2>
    <div class="stats-grid">
        <div class="glass-stats">
            <i class="fab fa-python" style="font-size: 2rem;"></i>
            <h3 style="margin: 8px 0;">Programming</h3>
            <div style="display: flex; flex-wrap: wrap; gap: 8px; justify-content: center;">
                <span class="tech-pill">Python</span>
                <span class="tech-pill">Java</span>
                <span class="tech-pill">JavaScript</span>
                <span class="tech-pill">Bash</span>
            </div>
        </div>
        <div class="glass-stats">
            <i class="fas fa-shield-haltered" style="font-size: 2rem;"></i>
            <h3 style="margin: 8px 0;">Cyber Security</h3>
            <div style="display: flex; flex-wrap: wrap; gap: 8px; justify-content: center;">
                <span class="tech-pill">Wazuh</span>
                <span class="tech-pill">ELK Stack</span>
                <span class="tech-pill">Zabbix</span>
                <span class="tech-pill">AlienVault</span>
                <span class="tech-pill">Metasploit</span>
            </div>
        </div>
        <div class="glass-stats">
            <i class="fas fa-cloud" style="font-size: 2rem;"></i>
            <h3 style="margin: 8px 0;">Systems & Cloud</h3>
            <div style="display: flex; flex-wrap: wrap; gap: 8px; justify-content: center;">
                <span class="tech-pill">Linux/Kali</span>
                <span class="tech-pill">Active Directory</span>
                <span class="tech-pill">AWS (IAM/EC2)</span>
                <span class="tech-pill">Docker</span>
            </div>
        </div>
    </div>

    <hr>

    <!-- FEATURED PROJECTS (real & impressive) -->
    <h2 style="display: flex; gap: 12px; margin-bottom: 1rem;"><i class="fas fa-rocket"></i> FLAGSHIP PROJECTS</h2>
    <div class="stats-grid">
        <div class="project-card">
            <i class="fas fa-user-ninja" style="font-size: 2rem; color: #6c63ff;"></i>
            <h3 style="margin: 12px 0 6px;">🕶️ Anonymous Red Team Env</h3>
            <p>Isolated hacking lab using Qubes OS + sys-whonix. Full attack/defense simulation with SIEM monitoring integration (Wazuh + ELK).</p>
            <div style="margin-top: 12px;"><span class="badge">Red Teaming</span> <span class="badge">SIEM</span></div>
        </div>
        <div class="project-card">
            <i class="fas fa-dna" style="font-size: 2rem; color: #6c63ff;"></i>
            <h3 style="margin: 12px 0 6px;">🧬 AI Chronic Disease System</h3>
            <p>ML-based early disease prediction (Random Forest & XGBoost) with real-time risk analysis dashboard.</p>
            <div><span class="badge">Machine Learning</span> <span class="badge">Python/Flask</span></div>
        </div>
        <div class="project-card">
            <i class="fas fa-robot" style="font-size: 2rem; color: #6c63ff;"></i>
            <h3 style="margin: 12px 0 6px;">🛡️ AI Security Scanner</h3>
            <p>Real-time threat detection engine monitoring network flows + process anomalies using isolation forest algorithm.</p>
            <div><span class="badge">AI Anomaly</span> <span class="badge">Network Sec</span></div>
        </div>
    </div>

    <hr>

    <!-- GITHUB STATS + ACTIVITY (clean embed with fallback) -->
    <div class="stats-grid">
        <div class="glass-stats">
            <i class="fab fa-github-alt"></i>
            <h3>📊 GitHub Analytics</h3>
            <img src="https://github-readme-stats.vercel.app/api?username=sarankumar-2209&show_icons=true&theme=radical&bg_color=0a0a1a&title_color=6c63ff&icon_color=6c63ff&border_radius=16&hide_border=true" width="100%" style="border-radius: 20px; margin-top: 8px;" alt="github stats">
        </div>
        <div class="glass-stats">
            <i class="fas fa-chart-simple"></i>
            <h3>📈 Top Languages</h3>
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sarankumar-2209&layout=compact&theme=radical&bg_color=0a0a1a&title_color=6c63ff&hide_border=true&border_radius=16" width="100%" style="border-radius: 20px;" alt="top langs">
        </div>
    </div>

    <!-- activity graph - dynamic svg from github-readme-activity-graph -->
    <div class="glass-stats" style="margin: 1.2rem 0;">
        <h3><i class="fas fa-chart-line"></i> CONTRIBUTION ACTIVITY</h3>
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=sarankumar-2209&theme=react-dark&bg_color=060514&color=9b8cff&line=6c63ff&point=c084fc&area=true&hide_border=true" width="100%" style="border-radius: 20px;" alt="activity graph">
    </div>

    <!-- Snake Contribution Graph (official via github) -->
    <div class="glass-stats" style="margin: 1.2rem 0; text-align: center;">
        <h3><i class="fas fa-gamepad"></i> SNAKE EATING CONTRIBUTIONS 🐍</h3>
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg">
            <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg">
            <img alt="github contribution snake" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg" style="max-width: 100%; border-radius: 24px; background: #0b0920;">
        </picture>
        <p style="font-size: 0.7rem; margin-top: 8px;">✨ contribution snake animation — keep the streak alive!</p>
    </div>

    <!-- TROPHIES section: GitHub Profile Trophy -->
    <div class="glass-stats" style="margin: 1rem 0;">
        <h3><i class="fas fa-trophy"></i> CYBER ACHIEVEMENTS</h3>
        <img src="https://github-profile-trophy.vercel.app/?username=sarankumar-2209&theme=radical&no-frame=true&row=2&column=4&margin-w=10&margin-h=10" width="100%" style="border-radius: 16px;" alt="trophies">
    </div>

    <hr>

    <!-- CONNECT SECTION : GitHub friendly + interactive -->
    <div style="background: rgba(0, 0, 0, 0.4); border-radius: 2rem; padding: 1.6rem; margin-top: 1rem; text-align: center;">
        <h2><i class="fas fa-address-card"></i> NETWORK & CONTACT</h2>
        <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 1.2rem; margin: 1.5rem 0;">
            <a href="mailto:saran2209kumar@gmail.com" class="social-icon"><i class="fas fa-envelope"></i> Email</a>
            <a href="#" class="social-icon" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn: Saran Kumar</a>
            <a href="https://github.com/sarankumar-2209" class="social-icon" target="_blank"><i class="fab fa-github"></i> GitHub</a>
        </div>
        <div class="footer-quote">
            <i class="fas fa-shield-alt"></i> "Offensive mindset, defensive architecture — Secure by design."
        </div>
    </div>

    <!-- Live hacker quote rotator (terminal style) -->
    <div style="margin-top: 1.6rem; background: #05030f; border-radius: 50px; padding: 0.8rem; text-align: center; font-family: 'JetBrains Mono';">
        <i class="fas fa-terminal"></i> <span id="hacker-quote">⏣ sudo nmap -sV --script vuln target</span> 
        <span style="animation: pulse 1s infinite;">_</span>
    </div>

    <!-- small footer line -->
    <div style="text-align: center; font-size: 0.7rem; margin-top: 2rem; opacity: 0.7; border-top: 1px dashed #2a2760; padding-top: 1rem;">
        ⚡ V. Sarankumar — Red Team | Threat Intelligence | Cloud Security
    </div>
</div>

<style>
    @keyframes pulse {
        0% { opacity: 1; }
        50% { opacity: 0; }
        100% { opacity: 1; }
    }
    img, picture img {
        max-width: 100%;
        height: auto;
    }
    a {
        text-decoration: none;
    }
    .glass-stats img {
        background: #05030f20;
    }
</style>

<script>
    // dynamic rotating terminal-like quotes for hacker vibe
    const quotes = [
        "🛡️ Analyzing SIEM alerts... anomaly detected",
        "⚔️ Active Directory Attack Path Simulation",
        "🔍 Threat Hunting: scanning for persistence",
        "☁️ AWS IAM privilege escalation check",
        "🐍 Python AI Scanner: real-time protection",
        "📡 Wireshark capture: 0x7F packets filtered",
        "🧨 Red Team engaged: C2 beacon deployed (lab only)"
    ];
    let idx = 0;
    const quoteEl = document.getElementById('hacker-quote');
    if(quoteEl) {
        setInterval(() => {
            quoteEl.style.opacity = '0.8';
            setTimeout(() => {
                quoteEl.textContent = quotes[idx % quotes.length];
                idx++;
                quoteEl.style.opacity = '1';
            }, 150);
        }, 3800);
    }

    // tiny hover effect on all cards to feel interactive
    const cards = document.querySelectorAll('.project-card, .glass-stats');
    cards.forEach(card => {
        card.addEventListener('mouseenter', () => {
            card.style.transition = 'all 0.2s ease';
        });
    });
    console.log("%c🔥 GitHub Profile Ready | Sarankumar — Cyber Security Arsenal", "color: #6c63ff; font-size: 14px; font-family: monospace;");
</script>

<!-- 
    ADDITIONAL NOTE: 
    This HTML is fully self-contained and optimized for GitHub profile README display (via markdown embedding or as a standalone).
    All stats & graph APIs are publicly accessible using 'sarankumar-2209' as username.
    Snake graph uses official platane/snk output. Everything respects GitHub's design language + dark mode friendly.
-->
</body>
</html>
