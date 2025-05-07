<p align="center">
  <img src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="480" alt="Coding Magic" />
</p>

<h1 align="center">I'm <span style="color:#FFB6C1;">Aleyna Turan</span> 👋</h1>
<h3 align="center">Full-Stack Developer & Interactive Game Creator from Turkey</h3>

---

### About Me

- 💻 **Full-stack developer** building both front- & back-end applications  
- 🕹️ **Game developer** crafting interactive experiences with Unity & Unreal Engine  
- 📚 **Lifelong learner**, currently diving into JavaScript & TypeScript  

---

### 🐍 Contribution Snake

![Contribution Snake](dist/github-contribution-grid-snake.svg)

To enable, add this workflow at **.github/workflows/generate-snake.yml**:

```yaml
name: Generate Contribution Snake
on:
  schedule:
    - cron: '0 0 * * *'  # every day at midnight UTC
  push:
    branches:
      - main
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Generate snake SVG
        uses: platane/snk@v3
        with:
          output-image: dist/github-contribution-grid-snake.svg
      - name: Commit & push SVG
        run: |
          git config user.name github-actions
          git config user.email actions@users.noreply.github.com
          git add dist/github-contribution-grid-snake.svg
          git commit -m "chore: update contribution snake"
          git push
```  

---

### ⚙️ Tech Stack

**Languages:** JavaScript | TypeScript | C# | C++ | Java  
**Frameworks & Engines:** React | Next.js | React Native | Unity | Unreal Engine  
**Databases & Tools:** MongoDB | MySQL | Oracle | Firebase | Android Studio  

---

### 🔗 Connect With Me

- 🌐 Portfolio & Blog: [aleyna.dev](https://aleyna.dev)  
- 👩‍💻 GitHub: [github.com/aleyna-tturan](https://github.com/aleyna-tturan)  
- ✉️ Email: turanaleyna469@gmail.com  
- 📸 Instagram: [@turanmisslina](https://instagram.com/turanmisslina)  

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aleyna-tturan&theme=radical&show_icons=true&hide_border=true" alt="GitHub stats" />  
  <br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aleyna-tturan&theme=radical&hide_border=true" alt="Streak stats" />  
  <br>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=aleyna-tturan&theme=radical" alt="Profile summary" />
</p>

---

### ✨ Final Words

> "Coding turns ideas into reality and challenges into achievements."  
> "Kodlama, fikirleri gerçeğe, zorlukları başarıya dönüştürür."  

---

### 👀 Profile Visits

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=aleyna-tturan&color=green" alt="Profile views" />
</p>

---

### 📌 Pinned Projects

<p align="center">
  [![Museum Guide](https://img.shields.io/badge/Museum%20Guide-React%20Native-FFB6C1?style=flat-square)](https://github.com/aleynaturan/museum-guide)
  [![Raccoon Rascal](https://img.shields.io/badge/Raccoon%20Rascal-Unity-1CA3EC?style=flat-square)](https://github.com/aleynaturan/raccoon-adventure)
  [![Portfolio](https://img.shields.io/badge/Portfolio-Vue%20%26%20GSAP-98FF98?style=flat-square)](https://github.com/aleynaturan/portfolio)
</p>
