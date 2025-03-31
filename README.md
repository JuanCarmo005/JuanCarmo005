## Olá! Eu sou Juan Carmo 005

- 🔭 Estou cursando Ciencia da computaçao
- 🌱 Aprendendo python
- ⚡ Estou sempre buscando aprender coisas novas


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=JuanCarmo005&show_icons=true&theme=tokyonight)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=JuanCarmo005&layout=donut)](https://github.com/anuraghazra/github-readme-stats)

name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: JuanCarmo005
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
</div>
