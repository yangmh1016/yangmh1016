<p align="center">
  <svg width="850" height="200" viewBox="0 0 850 200" fill="none" xmlns="http://www.w3.org/2000/svg">
    <style>
      .terminal-bg { fill: #0d1117; stroke: #30363d; stroke-width: 2; rx: 8px; }
      .terminal-header { fill: #161b22; rx: 8px; }
      .circle-r { fill: #ff5f56; } .circle-y { fill: #ffbd2e; } .circle-g { fill: #27c93f; }
      .term-title { fill: #8b949e; font-family: monospace; font-size: 13px; }
      .text-green { fill: #39ff14; font-family: 'Courier New', monospace; font-size: 14px; font-weight: bold; }
      .text-dim { fill: #58a6ff; font-family: 'Courier New', monospace; font-size: 13px; }
      .text-white { fill: #c9d1d9; font-family: 'Courier New', monospace; font-size: 13px; }
      
      /* 控制命令流滚动的核心动画 */
      @keyframes scrollText {
        0% { transform: translateY(0px); }
        10% { transform: translateY(0px); }
        25% { transform: translateY(-25px); }
        40% { transform: translateY(-50px); }
        55% { transform: translateY(-75px); }
        70% { transform: translateY(-100px); }
        85% { transform: translateY(-125px); }
        100% { transform: translateY(-150px); }
      }
      .scroll-container { animation: scrollText 14s infinite steps(1); }
      
      /* 光标闪烁动画 */
      @keyframes blink { 0%, 49% { opacity: 1; } 50%, 100% { opacity: 0; } }
      .cursor { animation: blink 1s infinite; fill: #39ff14; }
    </style>
    
    <rect width="850" height="200" class="terminal-bg"/>
    <path d="M0 8C0 3.58172 3.58172 0 8 0H842C846.418 0 850 3.58172 850 8V30H0V8Z" class="terminal-header"/>
    <circle cx="20" cy="15" r="6" class="circle-r"/>
    <circle cx="40" cy="15" r="6" class="circle-y"/>
    <circle cx="60" cy="15" r="6" class="circle-g"/>
    <text x="425" y="20" text-anchor="middle" class="term-title">yang@cyberspace:~ (zsh)</text>
    
    <svg x="20" y="50" width="810" height="130" viewBox="0 0 810 130" style="overflow: hidden;">
      <g class="scroll-container">
        <g transform="translate(0, 20)">
          <text class="text-green">$ whoami</text>
          <text x="90" class="text-white">yang --status=ACTIVE --role="Cyber-Architect"</text>
        </g>
        <g transform="translate(0, 45)">
          <text class="text-green">$ systemctl status core-matrix.service</text>
        </g>
        <g transform="translate(0, 70)">
          <text class="text-dim">● core-matrix - Loaded & Active (Running on 127.0.0.1)</text>
        </g>
        <g transform="translate(0, 95)">
          <text class="text-dim">🔑 SSH_AUTH_SOCK: Connected into neural network...</text>
        </g>
        <g transform="translate(0, 120)">
          <text class="text-green">$ git log --all --graph --decorate --oneline</text>
        </g>
        <g transform="translate(0, 145)">
          <text class="text-white">* 86459e5 (HEAD -> main) feat: adaptive auto-green system</text>
        </g>
        <g transform="translate(0, 170)">
          <text class="text-white">* 80366b3 chore: matrix routine optimization completed</text>
        </g>
        <g transform="translate(0, 195)">
          <text class="text-green">$ initializing grid wall injection...</text>
          <rect x="290" y="-12" width="8" height="15" class="cursor"/>
        </g>
      </g>
    </svg>
  </svg>
</p>

---

<p align="center">
  <a href="https://github.com/yang">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=39FF14&background=0D111700&center=true&vCenter=true&width=700&lines=INITIALIZING+CYBERSPACE+INTERFACE...;LOADING+DATABASE+METRICS+FOR+YANG...;NEURAL+NETWORKS:+ACTIVE;KEEP+COMMITTING.+KEEP+INFILTRATING." alt="Typing SVG" />
  </a>
</p>

### 💻 $ env | grep TECHNICAL_STACK

<p align="left">
  <img src="https://img.shields.io/badge/Shell_Script-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white&box-shadow=0+0+10px+#39ff14" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux_HPC-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

### 📊 $ monitor --realtime --target=yang

<table border="0" width="100%">
  <tr>
    <td width="50%" align="center" valign="top">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=yang&theme=calm-dark&fire=39FF14&currStreakNum=39FF14&sideNums=39FF14&sideLabels=8b949e&dates=8b949e&hide_border=true" width="100%" alt="yang's streak" />
    </td>
    <td width="50%" align="center" valign="top">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yang&layout=compact&theme=matrix&hide_border=true" width="100%" alt="yang's top languages" />
    </td>
  </tr>
  <tr>
    <td colspan="2" width="100%" align="center" valign="top">
      <img src="https://github-readme-stats.vercel.app/api?username=yang&show_icons=true&theme=matrix&hide_border=true&count_private=true" width="100%" alt="yang's github stats" />
    </td>
  </tr>
</table>

---

### 🌐 $ netstat -antp | grep github

```bash
Proto Recv-Q Send-Q Local Address           Foreign Address         State      
tcp        0      0 127.0.0.1:443           140.82.113.4:443        ESTABLISHED
tcp        0    120 127.0.0.1:22            140.82.112.3:22         ESTABLISHED

[SYSTEM INFO] Matrix established. Connection encrypted. 
[STATUS] Grid wall injection loop running flawlessly.
