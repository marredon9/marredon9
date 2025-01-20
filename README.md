
<p align="center">
  <img src="https://github.com/user-attachments/assets/a3a60c27-5209-47e4-bbdb-877d85eaad21" alt="Working Work From Home GIF by Pudgy Penguins" width="250">
</p>

  <div style="width: 60%; text-align: justify;">
    <h1>🚀 Welcome, Code Explorer! 🌍</h1>
    <p>
      Hey there! Glad to have you here. This GitHub corner is where my ideas, experiments, and projects come to life.<br>
      From web development to unexpected creations, there’s always something in the works.
    </p>
    <h2>🌟 What can you do here?</h2>
    <p>✅ Explore the code and discover something new</p>
    <p>✅ Report issues or suggest improvements (all feedback is welcome!)</p>
    <p>✅ Contribute if you like what you see 💡</p>
    <p>
      If you find this repository useful or interesting, don’t forget to leave a ⭐.<br>
      Ideas grow better when shared. 🚀
    </p>
    <p>See you in the code! 😃</p>
  </div>
</div>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.marredon9 }}

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
