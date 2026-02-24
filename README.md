<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Learning%20Developer&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Python%20%7C%20Django%20%7C%20Data%20Science&descAlignY=60&descSize=20&descColor=a78bfa"/>

<!-- Typing Animation -->
<a href="https://github.com/sulavg50-ux">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=A78BFA&center=true&vCenter=true&random=false&width=500&lines=print(%22Hello%2C+World!%22);Learning+Python+%F0%9F%90%8D;Building+with+Django+%F0%9F%8C%90;Exploring+Data+Science+%F0%9F%93%8A;Keep+Growing+Every+Day+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<!-- Snake Animation (requires GitHub Actions setup - instructions below) -->
<!-- 
  To enable the snake animation, add this to .github/workflows/snake.yml:
  See instructions at bottom of this file
-->

<br/>

<!-- About Me Section -->
<table>
<tr>
<td width="50%" valign="top">

## 🌙 About Me

```python
class LearningDeveloper:
    def __init__(self):
        self.name     = "Your Name"
        self.role     = "Learning Developer"
        self.learning = [
            "Python 🐍",
            "Django 🌐",
            "Data Science 📊"
        ]
        self.goals    = "Keep Growing 🚀"
    
    def say_hi(self):
        print("Thanks for visiting! 👋")

me = LearningDeveloper()
me.say_hi()
```

</td>
<td width="50%" valign="top">

## 💻 Keep Coding!

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYm1iM2ZtdWloNzZpODg0YmFoYTM3NmNkcWoxYmhoOTd6MDgza2p4MCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/cnhpl4IeYgU7MCBdV2/giphy.gif" width="100%" />

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### Languages & Frameworks
<p>
  <img src="https://skillicons.dev/icons?i=python,django,html,css,js&perline=5&theme=dark" />
</p>

### Tools & Platforms
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,linux,postgresql&perline=5&theme=dark" />
</p>

### Data Science
<p>
  <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,numpy&perline=5&theme=dark" />
</p>

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=sulavg50-ux&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sulavg50-ux&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117"/>
</div>

<br/>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sulavg50-ux&theme=tokyonight&hide_border=true&background=0d1117&stroke=a78bfa&ring=a78bfa&fire=ff6b6b&currStreakLabel=a78bfa" />
</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=sulavg50-ux&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&column=7"/>
</div>

---

## 🌱 What I'm Learning

<div align="center">

| 🐍 Python | 🌐 Django | 📊 Data Science |
|:---------:|:---------:|:---------------:|
| ![](https://geps.dev/progress/65) | ![](https://geps.dev/progress/40) | ![](https://geps.dev/progress/30) |
| Core + OOP | REST APIs | Pandas & NumPy |

</div>

---

## 🤝 Let's Connect!

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-sulavg50--ux-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sulavg50-ux)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sulav-giri-1700993b3)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/sulavg50-ux)

</div>

---

## 🐍 My Contributions Snake

<div align="center">

<!-- After setting up GitHub Actions, replace the src below with your actual snake gif URL -->
<img src="https://raw.githubusercontent.com/sulavg50-ux/sulavg50-ux/output/github-contribution-grid-snake-dark.svg" alt="Snake animation"/>

</div>

---

<div align="center">

### 👀 Profile Views
![Profile Views](https://komarev.com/ghpvc/?username=sulavg50-ux&color=a78bfa&style=for-the-badge&label=PROFILE+VIEWS)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer"/>

</div>

<!--
=======================================================
🐍 SNAKE ANIMATION SETUP (Optional but looks amazing!)
=======================================================

1. Create file: .github/workflows/snake.yml
2. Paste this content:

name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 10

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
=======================================================
-->
