- Enable the default footer text:

  ```md
  ---
  footer: true
  ---
  ```

- Customize footer text without displaying copyright information:

  ```md
  ---
  footer: This site is served by GitHub Pages
  copyright: false
  medialink: false
  ---
  ```

- Custom footer content and copyright information:

  ```md
  ---
  footer: <a href="https://github.com/Mister-Hope"> Mr.Hope </a>
  copyright: MIT LICENSE
  ---
  ```

- When you set `displayFooter` to true in the theme, you can also disable it locally:

  ```md
  ---
  footer: false
  ---
  ```

- To remove the default footer content while keeping copyright information displayed, please use an empty string.

  ```md
  ---
  footer: ""
  ---
  ```