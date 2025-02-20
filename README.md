
## 🌐Socials
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/nikelf_) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/nithinm07) [![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?logo=Reddit&logoColor=white)](https://reddit.com/user/Candid_Ad5694) [![Twitch](https://img.shields.io/badge/Twitch-%239146FF.svg?logo=Twitch&logoColor=white)](https://twitch.tv/devthenik) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/SuzuElfed) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/c/NykSan) 

# 📊GitHub Stats :
![](https://github-readme-stats.vercel.app/api?username=nyksans&theme=radical&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=nyksans&theme=radical&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

### ✍️Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)

---
[![](https://visitcount.itsvg.in/api?id=nyksans&icon=0&color=0)](https://visitcount.itsvg.in)

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
