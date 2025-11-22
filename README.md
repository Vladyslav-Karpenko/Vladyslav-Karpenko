# Hi there 👋, my name is Vladyslav
## Full Stack Developer

The profession of an IT developer has become for me not only a job, but also a true life passion. 
I enjoy writing clean, elegant code, improving every detail, and bringing ideas to perfection.

---

## 📢 Connect with me

[![Gmail](https://img.shields.io/badge/Gmail-vladyslav.karpenko.cz%40gmail.com-red?logo=gmail)](mailto:vladyslav.karpenko.cz@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vladyslav%20Karpenko-blue?logo=linkedin)](#)
[![GitHub](https://img.shields.io/badge/GitHub-Vladyslav--Karpenko-black?logo=github)](https://github.com/Vladyslav-Karpenko)

---

## 🔧 My Skill Set

### **Frontend**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled--Components-DB7093?logo=styled-components&logoColor=white)

### **Backend**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

### **Tools**
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white)
![AutoCAD](https://img.shields.io/badge/AutoCAD-E51050?logo=autodesk&logoColor=white)
![GIS6](https://img.shields.io/badge/GIS6-4A90E2?logo=mapbox&logoColor=white)

---

## 📊 My GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Vladyslav-Karpenko&show_icons=true&theme=tokyonight)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Vladyslav-Karpenko&layout=compact&theme=tokyonight)

---

## 👾 Animated Header

<img src="https://readme-typing-svg.herokuapp.com?color=%236AF7FF&lines=Full+Stack+Developer;Passionate+about+clean+code;Always+learning+new+tech" />

---

## 🔗 Visitors

![Visitors](https://komarev.com/ghpvc/?username=Vladyslav-Karpenko&color=blue)

---

## 🔥 Fun Animation

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="400" />

---

## 📚 About Me

- 💻 I love developing modern web applications
- 🎓 I constantly improve my skills in JS
- 💭 I enjoy working on UI/UX and animations
- 👥 Open to collaboration and new opportunities

---


## 📦 Extra: Contribution Snake Animation

> ⚠️ The snake animation link shows **404** because you don’t yet have the GitHub Action that generates the SVG.
>
> Add this workflow to your repository at:
> **.github/workflows/snake.yml**

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - uses: Platane/snk@v3
        with:
          github_user_name: Vladyslav-Karpenko
          outputs: dist/snake.svg

      - name: Upload artifact
        uses: actions/upload-artifact@v4
        with:
          name: snake
          path: dist/snake.svg

      - name: Deploy snake animation to GitHub Pages branch
        uses: crazy-max/ghaction-github-pages@v3
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          target_branch: output
          build_dir: dist
```

After workflow runs once, use this in your README:

```md
![snake gif](https://github.com/Vladyslav-Karpenko/Vladyslav-Karpenko/blob/output/snake.svg)
```
