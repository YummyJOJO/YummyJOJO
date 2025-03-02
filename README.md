<p align = "center">
<img src="https://github.com/YummyJOJO/YummyJOJO/blob/master/image.jpg" align = "center" width = "40%"/>
</p>
<p><em>A PhD student majoring in Computer Science. 😊</br>
</em></p>


```javascript
const aboutMe = {
   pronouns: "he" | "him",
   code: [Javascript, Typescript, HTML, CSS, Python, Java, CSharp, Kotlin, Swift],
   technologies: {
      frontEnd: {
         js: ["React", "Angular"],
         css: ["Materialize", "Bulma", "Bootstrap", "Material Design", "Semantic UI"]
      },
      backEnd: {
         java: ["Spring"],
         js: ["Node", "Express"],
         csharp: ["Asp.net Core"],
         misc: ["Bash", "Puppeteer", "Selenium", "Cypress"]
      },
      databases: ["MongoDB", "mySQL", "SQLServer"],
      mobile: ["Android", "IOS"]
   },
   currentOccupation: ["Phd student, open for job opportunities"],
   challenge: "I'm working towards being able to body building.",
};
```
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
</picture>

_generated with [Platane/snk](https://github.com/Platane/snk)_

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.YummyJOJO }}

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
