<div align="center">
  <img alt-"html5" src="https://media.giphy.com/media/XAxylRMCdpbEWUAvr8/giphy.gif" width="80" title="html">
  <img alt="css" src="https://media.giphy.com/media/fsEaZldNC8A1PJ3mwp/giphy.gif" width="80" title="css">
  <img alt="VSCode" src="https://i.giphy.com/media/IdyAQJVN2kVPNUrojM/200.webp" width="80" title="vscode">
  <img alt="python" src="https://i.giphy.com/media/LMt9638dO8dftAjtco/200.webp" width="80" title="python">
  <img alt="javascript" src="https://media3.giphy.com/media/ln7z2eWriiQAllfVcn/200w.webp" width="80" title="javascript">
  <img alt="sublime" src="https://media.giphy.com/media/jnDKffgCfGYOp6cMTK/giphy.gif" width="80" title="sublime">
  <img alt="github" src="https://i.giphy.com/media/KzJkzjggfGN5Py6nkT/200.webp" width="80" title="github">
  <img alt="node" src="https://media.giphy.com/media/kdFc8fubgS31b8DsVu/giphy.gif" width="80" title="node">
</div>

- 👋 Hi, I’m @likailang1026
- 👀 I’m interested in AI, Roborts and CV
- 🌱 I’m currently learning ai in ELTE
- 💞️ I’m looking to collaborate on programming
- 📫 Nice to see you!


[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)       
<!---
likailang1026/likailang1026 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
