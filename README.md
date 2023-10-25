name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v2
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v2.6.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          <h2 align="left">Hi 👋! My name is Maaz Khan</h2>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MaazKhan878&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&locale=en&hide_border=false" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=MaazKhan878&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph"  />
</div>

###

<img align="right" height="150" src="https://www.google.com/search?q=create+new+idea+picture&tbm=isch&ved=2ahUKEwjNqbGwgZKCAxU4dqQEHYv0CVwQ2-cCegQIABAA&oq=create+new+idea+picture&gs_lcp=CgNpbWcQAzoECCMQJzoHCCMQ6gIQJzoHCAAQigUQQzoKCAAQigUQsQMQQzoNCAAQigUQsQMQgwEQQzoICAAQsQMQgwE6CwgAEIAEELEDEIMBOgQIABADOgUIABCABDoICAAQgAQQsQM6BQgAELEDOgYIABAIEB46BggAEAUQHjoHCAAQGBCABFDcBljUhQFgqocBaAdwAHgEgAGMAogBlzySAQQyLTM0mAEAoAEBqgELZ3dzLXdpei1pbWewAQrAAQE&sclient=img&ei=3nY5Zc3CHbjskdUPi-mn4AU&bih=745&biw=1536&client=firefox-b-d#imgrc=mr1rey89UKGPWM"  />

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="30" alt="c logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="30" alt="vscode logo"  />
</div>

###

<div align="left">
  <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="youtube logo"  />
  <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitch&logo=twitch&label=&color=9146FF&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="twitch logo"  />
  <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="discord logo"  />
  <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
</div>

###

<br clear="both">

<img src="https://raw.githubusercontent.com/MaazKhan878/MaazKhan878/output/snake.svg" alt="Snake animation" />

###
