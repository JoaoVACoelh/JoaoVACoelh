
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=2aA9F7&height=120&section=header"/>
<div align="center">
  <h1>
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=35&duration=2500&pause=1000&color=2EA9F7&center=true&vCenter=true&width=600&height=60&lines=Hello%2C+my+name+is+Jo%C3%A3o+Vitor;I'm+18+years+old;+I'm+from+Brazil+" alt="Typing SVG" /></a>
  </h1>
</div>

<div align="left">
  👀 Focado nos Estudos<br/>
  🌱 Atualmente Estudando Linguagens como Php e C#
</div>
<br/>

<div align="center">
  <a href="https://github.com/JoaoVACoelh">
  <img loading="lazy" height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JoaoVACoelh&layout=compact&langs_count=7&theme=tokyonight"/></a>
  <img loading="lazy" height="160em" src="https://github-readme-stats.vercel.app/api?username=JoaoVACoelh&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
</div>

<div align="center">
<a href="https://instagram.com/joao.arantes__/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href = "https://mail.google.com/mail/u/0/#inbox?compose=CllgCJTJFfhdhWzgFQjjGJjGfpwhwzGfnGbBpdzVvzzFkVHXLkBGHPrvFnzLRTVZmqSwSGWhqKg"><img loading="lazy" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/joão-vitor-arantes-coelho-070131274" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
</div>

uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.JoaoVACoelh }}

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

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
    
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>


<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=800080&height=120&section=footer"/>
