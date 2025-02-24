<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=2EAFB4&center=true&vCenter=true&random=false&width=435&lines=Hi+there%2C+I'm+Anbasss!+%F0%9F%91%8B;Welcome+to+my+GitHub+profile!" alt="Typing SVG" />
</div>



<p align="center">
  <img src="https://komarev.com/ghpvc/?username=anbasss&label=Profile%20views&color=2eafb4&style=flat" alt="Profile views" />
</p>

## 🚀 About Me
```python
class Anbas:
    def __init__(self):
        self.name = "Anbas"
        self.role = "Software Developer"
        self.languages = ["JavaScript", "Python", "HTML", "CSS"]
        self.learning = ["React", "Node.js", "Express", "Cloud Computing"]
        self.hobbies = ["Chess", "Hiking", "Cycling"]
```

## 🔥 My Stats
<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=anbasss&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anbasss&layout=compact&langs_count=7&theme=tokyonight"/>
</div>

## 🛠️ Technologies & Tools
<div align="center">
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3" />
  <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</div>

## 📈 GitHub Contribution Graph
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=anbasss&theme=tokyo-night" />
</div>

## 🏆 GitHub Trophies
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=anbasss&theme=tokyonight&no-frame=true&row=1&&margin-w=30&no-bg=true" />
</div>

## 📫 Connect with me
<div align="center">
  <a href="mailto:anbasss@example.com">
    <img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/anbasss">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=2EAFB4&center=true&vCenter=true&random=false&width=435&lines=Thanks+for+visiting!;Feel+free+to+connect+with+me!" alt="Typing SVG" />
</div>

<!-- Note: To make the snake animation work, you need to:
1. Create a new repository named anbasss/anbasss
2. Set up a GitHub Action workflow for the snake animation
-->

```yaml name=.github/workflows/snake.yml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *" # every 12 hours
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: anbasss
          svg_out_path: dist/github-contribution-grid-snake-dark.svg
          snake_color: 'blue'

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
