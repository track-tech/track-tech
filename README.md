<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3000&pause=1000&color=2F81F7&center=true&vCenter=true&random=false&width=760&lines=Hi+%F0%9F%91%8B%2C+I%27m+Tracker;Robotics+%26+Embedded+Engineer;Wheel-Legged+Robot+Builder;Humanoid+Motion+Learning;Policies+that+run." alt="Typing SVG" />
<br />
<br />
<a href="https://track-tech.github.io/"><img src="https://img.shields.io/badge/Portfolio-FF6B6B?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a> <a href="https://www.cnblogs.com/startrack"><img src="https://img.shields.io/badge/Blog-__TRACKER-2F81F7?style=for-the-badge&logo=rss&logoColor=white" alt="Blog" /></a> <a href="https://space.bilibili.com/21198864"><img src="https://img.shields.io/badge/Bilibili-Videos-00A1D6?style=for-the-badge&logo=bilibili&logoColor=white" alt="Bilibili" /></a> <a href="https://github.com/track-tech?tab=repositories"><img src="https://img.shields.io/badge/Open_Source-181717?style=for-the-badge&logo=github&logoColor=white" alt="Open Source" /></a>
</div>

### 🚀 About Me

- **Robotics & embedded engineer** — wheel-legged robots, motion control, and teleoperation
- Built and open-sourced **[Venus-1](https://github.com/track-tech/Venus-1__Four-link-wheel-legged-robot)**, a four-link wheel-legged robot: mechanics, electronics and control, from scratch as an undergraduate thesis
- Authoring **[Uni-RoboController](https://github.com/track-tech/Uni-RoboController)** — an open teleoperation protocol, Android client, and conformance test suite
- Reproducing **SuperMimic** world-model RL on a 28-DoF humanoid (**RoboParty RP1**)
- Comfortable across the whole stack: mechanical design → embedded firmware → simulation & RL → full-stack tooling

<details>
  <summary><b>中文版个人简介（点击展开）</b></summary>
  <br />
  <p>我是 <b>Tracker</b>（GitHub 上的 <code>_TRACKER</code>），一个妄想点满技能树的人。</p>
  <p>本科毕业设计独立完成了一台四连杆轮腿机器人 <b>启明-1</b>：用 Pyslvs 拟合连杆、SolidWorks 建模、3mm 玻纤板做车身，STM32H723 + FreeRTOS 跑电控，用纯 PID 实现轮平衡、重心自适应、主动悬挂与跳跃。项目按 GPL-3.0 开源，拿到 70+ star。</p>
  <p>现在主要折腾两件事：一是 <b>机器人遥操作</b>，<a href="https://github.com/track-tech/Uni-RoboController">Uni-RoboController</a> 想用「公开协议 + 一致性测试」让不同形态的机器人被同一个 App 操作；二是 <b>具身智能</b>，把 SuperMimic 的世界模型强化学习复现到 28 自由度人形 RoboParty RP1 上。</p>
  <p>闲下来也喜欢写点工具：跑在 Cloudflare Workers 上的 AI 角色扮演 Agent（<a href="https://github.com/track-tech/meowfish-cloud">MeowFish</a>）、让机器人用无线 ADB 操作安卓手机的 AstrBot 插件、以及在 ESP32 上折腾 ESP-NOW 和 LVGL 的小玩意儿。</p>
</details>

> **Policies that run.** 把想法做成能跑的东西 —— from linkage synthesis and motor drivers to control laws and policies.

---

### 🔭 Current Work

- **[Uni-RoboController](https://github.com/track-tech/Uni-RoboController)** — open teleoperation protocol + Android client + conformance tests (design stage v0.1)
- **[SuperMimic @ RP1](https://github.com/track-tech/SuperMimic-RoboParty-RP1-)** — world-model RL and motion retargeting on a 28-DoF humanoid
- **Robot-facing AI tooling** — AstrBot plugins for wireless-ADB phone control and server monitoring dashboards

---

### ✨ Highlights

- 🦿 **Venus-1** — four-link wheel-legged robot, **74 ★ / 12 forks**, GPL-3.0, mechanical + electronics + code fully open-sourced
- 🤖 **SuperMimic @ RP1** — **0.758** norm-return over 40 LAFAN1 clips on a 28-DoF humanoid (G1 reference: 0.774)
- 📡 **Uni-RoboController** — one Android app for quadrupeds, humanoids, wheel-legged robots and arms, driven by a public protocol + CTS
- ☁️ **MeowFish Cloud** — AI role-play agent on Cloudflare Workers with a built-in SSH client and web terminal, zero cloud persistence
- 🏫 **IMAU_Course_Sharing** — a course-knowledge sharing community for Inner Mongolia Agricultural University

---

### 📸 Selected Open-Source Work

| Project | What it is |
|---|---|
| **[Venus-1](https://github.com/track-tech/Venus-1__Four-link-wheel-legged-robot)** | 四连杆轮腿机器人 · STM32H723 + FreeRTOS + PID，重心自适应 / 主动悬挂 / 跳跃 · 74 ★ |
| **[SuperMimic @ RoboParty RP1](https://github.com/track-tech/SuperMimic-RoboParty-RP1-)** | 把 SuperMimic 世界模型 RL 复现到 28-DoF 人形，一套代码支持 G1 / RP1 / RPO / Mars_v3 |
| **[Uni-RoboController](https://github.com/track-tech/Uni-RoboController)** | 开源机器人遥操作协议 + Android 操作端 + 一致性测试（CTS） |
| **[MeowFish Cloud](https://github.com/track-tech/meowfish-cloud)** | Cloudflare Workers 上的 AI 角色扮演 Agent，内置 SSH 客户端与 Web 终端（[在线体验](https://meowfish-agent.kdns.fr/)） |
| **[astrbot_plugin_server_monitor](https://github.com/track-tech/astrbot_plugin_server_monitor)** | AstrBot 服务器监控看板：SSH / Agent 双端采集、Docker、模型用量与余额、网页 SSH 终端 |
| **[astrbot_plugin_ruying](https://github.com/track-tech/astrbot_plugin_ruying)** | 让 AI 机器人通过无线 ADB「看见」并操作安卓手机：截屏、控件坐标、点击滑动 |
| **[Simple-ESP32C3-Controller](https://github.com/track-tech/Simple-ESP32C3-Controller)** | 把 9.9 元的玩具遥控器改成 ESP-NOW 无线手柄 |
| **[IMAU_Course_Sharing](https://github.com/track-tech/IMAU_Course_Sharing)** | 内蒙古农业大学课程攻略共享计划，把口口相传的课程经验变成公开资料 |

<details>
  <summary><b>📷 启明-1 实机照片（点击展开）</b></summary>
  <br />
  <p align="center">
    <img src="./assets/venus-1.jpg" width="80%" alt="启明-1 四连杆轮腿机器人" />
  </p>
</details>

---

### 🛠 Technical Stack

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=c,cpp,python,typescript,pytorch,ros,arduino,linux,docker,git,bash,cmake&theme=dark&perline=12" />
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=c,cpp,python,typescript,pytorch,ros,arduino,linux,docker,git,bash,cmake&theme=light&perline=12" />
    <img alt="Tech stack" src="https://skillicons.dev/icons?i=c,cpp,python,typescript,pytorch,ros,arduino,linux,docker,git,bash,cmake&theme=dark&perline=12" />
  </picture>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32" />
  <img src="https://img.shields.io/badge/FreeRTOS-3A9C4B?style=flat-square" alt="FreeRTOS" />
  <img src="https://img.shields.io/badge/micro--ROS-22314E?style=flat-square&logo=ros&logoColor=white" alt="micro-ROS" />
  <img src="https://img.shields.io/badge/CAN-FF6B00?style=flat-square" alt="CAN" />
  <img src="https://img.shields.io/badge/ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP-IDF" />
  <img src="https://img.shields.io/badge/MuJoCo_Warp-1F6FEB?style=flat-square" alt="MuJoCo Warp" />
  <img src="https://img.shields.io/badge/LAFAN1-6A5ACD?style=flat-square" alt="LAFAN1" />
  <img src="https://img.shields.io/badge/SolidWorks-005386?style=flat-square&logo=dassaultsystemes&logoColor=white" alt="SolidWorks" />
  <img src="https://img.shields.io/badge/Pyslvs-1F6FEB?style=flat-square" alt="Pyslvs" />
  <img src="https://img.shields.io/badge/Android_ADB-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android ADB" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=track-tech&show_icons=true&hide=prs,issues,contribs&theme=tokyonight&hide_border=true&custom_title=Tracker%27s%20GitHub%20Stats" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=track-tech&show_icons=true&hide=prs,issues,contribs&theme=default&hide_border=true&custom_title=Tracker%27s%20GitHub%20Stats" />
    <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=track-tech&show_icons=true&hide=prs,issues,contribs&theme=tokyonight&hide_border=true&custom_title=Tracker%27s%20GitHub%20Stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=track-tech&layout=compact&langs_count=8&count_weight=1&size_weight=0&theme=tokyonight&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=track-tech&layout=compact&langs_count=8&count_weight=1&size_weight=0&theme=default&hide_border=true" />
    <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=track-tech&layout=compact&langs_count=8&count_weight=1&size_weight=0&theme=tokyonight&hide_border=true" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=track-tech&theme=tokyonight&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=track-tech&theme=default&hide_border=true" />
    <img height="165" alt="GitHub streak" src="https://streak-stats.demolab.com?user=track-tech&theme=tokyonight&hide_border=true" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/track-tech/track-tech/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/track-tech/track-tech/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/track-tech/track-tech/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

### 🤝 Connect with Me

<p>
  <a href="https://github.com/track-tech"><img src="https://img.shields.io/badge/GitHub-track--tech-181717?style=flat&logo=github&logoColor=white" height="25" alt="GitHub" /></a>&nbsp;
  <a href="https://track-tech.github.io/"><img src="https://img.shields.io/badge/Portfolio-Personal_Homepage-blue?style=flat&logo=google-chrome&logoColor=white" height="25" alt="Portfolio" /></a>&nbsp;
  <a href="https://www.cnblogs.com/startrack"><img src="https://img.shields.io/badge/Blog-__TRACKER-2F81F7?style=flat&logo=rss&logoColor=white" height="25" alt="Blog" /></a>&nbsp;
  <a href="https://space.bilibili.com/21198864"><img src="https://img.shields.io/badge/Bilibili-00A1D6?style=flat&logo=bilibili&logoColor=white" height="25" alt="Bilibili" /></a>&nbsp;
  <a href="https://github.com/track-tech/track-tech/issues"><img src="https://img.shields.io/badge/Issues-Say_hi-2EA043?style=flat&logo=github&logoColor=white" height="25" alt="Issues" /></a>
</p>

<p align="center">
  <img alt="GitHub stars" src="https://img.shields.io/github/stars/track-tech?style=social&logo=github" />
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=track-tech&color=2F81F7&style=flat-square&label=PROFILE+VIEWS" />
</p>

---

<p align="center">
  <i>From linkage design to policies that run — building machines that actually move.</i> 🦿
</p>
