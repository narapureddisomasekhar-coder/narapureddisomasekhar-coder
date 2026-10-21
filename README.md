# 👋 Hey, I'm Praveen Akhil

### 💻 Aspiring SDE | ☕ Java & DSA | 🏎️ BMW Car Enthusiast

*Building skills. Building projects. Chasing the dream.*

---

## 🛠️ Tech Stack

<p>
<img src="https://skillicons.dev/icons?i=java,c,python,html,css,js,bootstrap,flask,sqlite,git,github,vscode" />
</p>

## 🎯 Currently

- 🧠 DSA with Java
- 💻 Building projects
- 🚀 Growing as a Software Engineer

## 🚀 Featured Project

**[🛒 AkhilMart](https://github.com/narapureddisomasekhar-coder/AkhilMart)**

Full-stack grocery shopping web application.

`Python` · `Flask` · `SQLite` · `HTML` · `CSS` · `Bootstrap`


## 📊 Contributions

name: Generate Contribution Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: narapureddisomasekhar-coder
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Publish snake files
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


## 🤝 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/praveen-akhil-narapureddi-2bb54336a?utm_source=share_via&utm_content=profile&utm_medium=member_android)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@codewithdinoo?si=Q0zf86ZU_vA-nQpw)

---

**💭 Code. Learn. Build. Repeat.**  
