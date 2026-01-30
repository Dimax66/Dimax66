<!-- =============================== -->
<!--    DIMAX66 — CYBER DASHBOARD  -->
<!-- =============================== -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=26&pause=800&color=00FFF7&center=true&vCenter=true&width=650&lines=SYSTEM+ONLINE;DIMAX66+CYBER+DASHBOARD;AUTOMATION+%7C+SERVERS+%7C+WEB+SYSTEMS;LOW+PROFILE+-+HIGH+CURIOUSITY" />

<br>

![Profile Views](https://komarev.com/ghpvc/?username=Dimax66&color=00FFF7&style=for-the-badge)

</div>

---

## ⚙️ TECHNOLOGY STACK

<div align="center">

![HTML](https://img.shields.io/badge/HTML5-000?style=for-the-badge&logo=html5&logoColor=00FFF7)
![CSS](https://img.shields.io/badge/CSS3-000?style=for-the-badge&logo=css3&logoColor=00FFF7)
![PHP](https://img.shields.io/badge/PHP-000?style=for-the-badge&logo=php&logoColor=00FFF7)
![Python](https://img.shields.io/badge/Python-000?style=for-the-badge&logo=python&logoColor=00FFF7)
![Linux](https://img.shields.io/badge/Linux-000?style=for-the-badge&logo=linux&logoColor=00FFF7)
![Nginx](https://img.shields.io/badge/Nginx-000?style=for-the-badge&logo=nginx&logoColor=00FFF7)
![MySQL](https://img.shields.io/badge/MySQL-000?style=for-the-badge&logo=mysql&logoColor=00FFF7)
![Apache](https://img.shields.io/badge/Apache-000?style=for-the-badge&logo=apache&logoColor=00FFF7)

</div>

---

## 🧠 SYSTEM INFO

```txt
User     : Dimax66
Mode     : Stealth
Status   : Active
Focus    : Automation / Infrastructure / Web Systems
Location : Unknown
Uptime   : Learning never stops
📊 GITHUB ANALYTICS
<div align="center"> <img src="https://github-readme-stats.vercel.app/api?username=Dimax66&show_icons=true&theme=tokyonight&hide_border=true" height="170"> <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dimax66&theme=tokyonight&hide_border=true" height="170"> </div>
🌐 ACTIVITY GRAPH
<div align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=Dimax66&theme=tokyo-night&hide_border=true"> </div>
🐍 CONTRIBUTION SNAKE
<div align="center"> <img src="https://raw.githubusercontent.com/Dimax66/Dimax66/output/github-contribution-grid-snake.svg"> </div>
🔗 CONNECT
🐙 GitHub → https://github.com/Dimax66

💬 Telegram → https://t.me/DefacerIndonesia1337

<div align="center">
⚡ DIMAX66 CYBER SYSTEM — 2026 ⚡
Silent work. Visible results.

</div> ```
🐍 Biar Ada ULAR JALAN (WAJIB SETUP)
Kalau mau kayak di gambar (ada animasi):

Buat File:
Path:

.github/workflows/snake.yml
Isi:
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - name: Generate snake
        uses: Platane/snk@v3
        with:
          github_user_name: Dimax66
          outputs: |
            dist/github-contribution-grid-snake.svg

      - name: Push output
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
