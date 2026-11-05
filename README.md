<div align="center">

# Hi, I'm Abhishek 👋

<a href="https://github.com/uniqabhishek">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=580&lines=Full-Stack+%26+AI+Systems+Engineer;Building+Real-Time+Voice+AI+(Groq+%2B+Deepgram);FinTech+%26+Algorithmic+Trading+Systems;React+%E2%80%A2+React+Native+%E2%80%A2+Flask+%E2%80%A2+WebSockets;Crafting+High-Performance+Software" alt="Typing SVG" />
</a>

<p align="center">
  <a href="https://uniqabhishek.github.io/Trading-Journal/"><img src="https://img.shields.io/badge/Live_App-TradeMind_AI-6366F1?style=for-the-badge&logo=rocket&logoColor=white" /></a>
  <a href="https://uniqabhishek.github.io/furniture-website/"><img src="https://img.shields.io/badge/Live_App-Grain_%26_Joint-2B1D14?style=for-the-badge&logo=safari&logoColor=white" /></a>
  <a href="mailto:abhisheksingh253648@gmail.com"><img src="https://img.shields.io/badge/Contact-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=uniqabhishek&label=Profile%20Views&color=38BDF8&style=for-the-badge" alt="Profile Views" />
</p>

---

</div>

## 👨‍💻 About Me

I am a **Full-Stack Developer and AI Systems Engineer** passionate about building cutting-edge conversational voice AI agents, full-stack trading software, and algorithmic financial systems.

- 🎙️ **Voice AI & LLM Systems**: Architected a **sub-second Real-Time Conversational Voice AI Agent** leveraging **Deepgram's Voice Agent API** (Nova-2 STT & Aura TTS), **Groq's LPU Inference Engine** (500+ tokens/sec), and full-duplex WebSockets.
- 🚀 **Production Web & Mobile Products**: Created **[TradeMind AI](https://uniqabhishek.github.io/Trading-Journal/)**, an institutional trading performance and psychology workspace across React, React Native (Expo), and Python Flask.
- 🤖 **Quantitative Algorithmic Systems**: Built **[QuantSignal](https://github.com/uniqabhishek/Trading-Bot)**, an automated quantitative market scanner combining CCXT exchange routing, multi-timeframe 200 EMA trend filters, and dynamic ATR risk control.
- 💼 **Current Status**: **Open for Opportunities** — actively interviewing for Full-Stack, AI Engineer, Frontend, and Python Software Engineering roles.

---

## 🏛️ System Architecture Showcase

```mermaid
flowchart LR
    subgraph Voice AI Agent
        V1[🎙️ Browser Mic] <-->|Binary WebSockets| V2[🐍 Flask WebSocket Gateway]
        V2 <-->|Nova-2 STT & Aura TTS| V3[⚡ Deepgram Voice Agent]
        V3 <-->|Ultra-Fast Reasoning| V4[🚀 Groq LPU LLM]
    end

    subgraph FinTech Ecosystem
        T1[📱 React Native & Web UI] <--> T2[⚡ TradeMind Psychology Engine]
        T3[📈 Market OHLCV Feeds] --> T4[🤖 QuantSignal 4-Layer Confluence]
        T4 -->|Automated Signals| T5[💬 Telegram Webhook & Alerts]
    end
```

---

## 🌟 Featured Engineering Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🎙️ Real-Time Conversational Voice AI Agent</h3>
      <p align="center">
        <a href="https://github.com/uniqabhishek/project-2">
          <img src="https://img.shields.io/badge/Repository-project--2-blue?style=flat-square&logo=github" alt="Repo" />
        </a>
        <a href="https://github.com/uniqabhishek/Python-Project">
          <img src="https://img.shields.io/badge/Mirror-Python--Project-blue?style=flat-square&logo=github" alt="Repo" />
        </a>
        <img src="https://img.shields.io/badge/Latency-Sub--Second-brightgreen?style=flat-square" alt="Latency" />
      </p>
      <p>A production-ready, conversational voice agent capable of human-like spoken dialogue without robotic pauses.</p>
      <ul>
        <li><b>Deepgram Voice Agent API</b>: Bidirectional streaming STT (Nova-2) and natural speech synthesis (Aura).</li>
        <li><b>Groq LPU Inference</b>: Lightning-fast LLM reasoning generating token streams at 500+ tokens/sec.</li>
        <li><b>WebSocket Audio Gateway</b>: Low-latency binary audio relay built on <code>flask-sock</code> without disk buffering.</li>
        <li><b>Hybrid Intelligence</b>: Fast token-aware local intent classification with seamless Groq LLM fallback.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">⚡ TradeMind AI — Trading Journal & Psychology Workspace</h3>
      <p align="center">
        <a href="https://uniqabhishek.github.io/Trading-Journal/">
          <img src="https://img.shields.io/badge/Live_Demo-uniqabhishek.github.io-success?style=flat-square&logo=github" alt="Live Demo" />
        </a>
        <a href="https://github.com/uniqabhishek/Trading-Journal">
          <img src="https://img.shields.io/badge/Repository-Trading--Journal-blue?style=flat-square&logo=github" alt="Repo" />
        </a>
      </p>
      <p>Modern trading performance and psychology workspace built for Crypto, Forex, and Stock traders.</p>
      <ul>
        <li><b>Cross-Platform</b>: Responsive React web app + Native Expo mobile application (Android/iOS) + Flask backend.</li>
        <li><b>Psychology Matrix</b>: Correlates emotional discipline (Confidence, FOMO, Revenge) with net P&L.</li>
        <li><b>Offline Encrypted Storage</b>: Operates seamlessly without server dependency using Async Storage.</li>
        <li><b>Stack</b>: React, React Native, Vite, Tailwind CSS, Python Flask, Render, Vercel.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🤖 QuantSignal AI — Quantitative Trading Engine & Bot</h3>
      <p align="center">
        <a href="https://github.com/uniqabhishek/Trading-Bot">
          <img src="https://img.shields.io/badge/Repository-Trading--Bot-blue?style=flat-square&logo=github" alt="Repo" />
        </a>
        <img src="https://img.shields.io/badge/Status-Production_Ready-green?style=flat-square" alt="Status" />
      </p>
      <p>An asynchronous quantitative market scanner and algorithmic Telegram signal bot built with Python 3.10+.</p>
      <ul>
        <li><b>4-Layer Quantitative Strategy</b>: 200 EMA Higher TF trend filter + RSI momentum + MACD cross + 1.5× volume surge.</li>
        <li><b>Dynamic ATR Risk Control</b>: Automated Stop-Loss (1.5× ATR) and Take-Profit (3.0× ATR) targeting a 1:2 R:R ratio.</li>
        <li><b>Multi-Exchange Failover</b>: CCXT integration with automatic failover (MEXC ➔ Gate.io).</li>
        <li><b>Stack</b>: Python, CCXT, Telegram API, Quart ASGI, Pandas, NumPy, Hypercorn.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🪑 Grain & Joint — Bespoke E-Commerce Web Experience</h3>
      <p align="center">
        <a href="https://uniqabhishek.github.io/furniture-website/">
          <img src="https://img.shields.io/badge/Live_Demo-uniqabhishek.github.io-success?style=flat-square&logo=github" alt="Live Demo" />
        </a>
        <a href="https://github.com/uniqabhishek/furniture-website">
          <img src="https://img.shields.io/badge/Repository-furniture--website-blue?style=flat-square&logo=github" alt="Repo" />
        </a>
      </p>
      <p>An editorial-grade e-commerce catalog for an artisanal solid wood furniture atelier.</p>
      <ul>
        <li><b>100/100 Lighthouse Performance</b>: Zero heavy framework dependencies; pure semantic HTML5 & modern CSS.</li>
        <li><b>Design Systems</b>: Custom CSS Grid & Flexbox, CSS variables color harmony, typography pairing (Fraunces & Work Sans).</li>
        <li><b>Mobile-First UX</b>: Fluid responsiveness across mobile, tablet, and desktop viewports.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🛠️ Technical Arsenal

<div align="left">

### AI & Machine Learning
![Deepgram](https://img.shields.io/badge/Deepgram_Voice_Agent-13EF95?style=for-the-badge&logo=deepgram&logoColor=black)
![Groq](https://img.shields.io/badge/Groq_LPU_Inference-F55036?style=for-the-badge&logo=fastapi&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-Llama_3_%7C_Mixtral-FF6F00?style=for-the-badge&logo=openai&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-Streaming_Audio-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Intent_Classification-blueviolet?style=for-the-badge)

### Languages & Core
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)

### Frontend & Mobile
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend & APIs
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Quart](https://img.shields.io/badge/Quart_(Async_ASGI)-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge&logo=flutter&logoColor=white)

### FinTech & Data Engineering
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![CCXT](https://img.shields.io/badge/CCXT-F0B90B?style=for-the-badge&logo=binance&logoColor=black)
![yfinance](https://img.shields.io/badge/Yahoo_Finance_API-410093?style=for-the-badge&logo=yahoo&logoColor=white)

### Tools & DevOps
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

## 📈 Activity & Contribution Streak

<div align="center">

<a href="https://github.com/uniqabhishek">
  <img src="https://streak-stats.demolab.com/?user=uniqabhishek&theme=radical&hide_border=true" alt="Abhishek's GitHub Streak" />
</a>

</div>

---

## 📬 Let's Connect & Collaborate!

I am actively interviewing for **Full-Stack Engineer, AI Software Engineer, and Python Developer** roles.

<p align="left">
  <a href="mailto:abhisheksingh253648@gmail.com">
    <img src="https://img.shields.io/badge/Email-abhisheksingh253648%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://uniqabhishek.github.io/Trading-Journal/">
    <img src="https://img.shields.io/badge/Live_App-TradeMind_AI-4F46E5?style=for-the-badge&logo=safari&logoColor=white" />
  </a>
  <a href="https://uniqabhishek.github.io/furniture-website/">
    <img src="https://img.shields.io/badge/Live_App-Grain_%26_Joint-2B1D14?style=for-the-badge&logo=safari&logoColor=white" />
  </a>
  <a href="https://github.com/uniqabhishek">
    <img src="https://img.shields.io/badge/GitHub-uniqabhishek-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>"Speed, precision, and clean code — building intelligent systems that scale."</i>
</p>
