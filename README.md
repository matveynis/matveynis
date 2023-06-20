
<!-- Заголовок -->
# Привет, я Матвей, студент 4 курса и программист с опытом выполнения лабараторных и codewars :>

<!-- Значок CodeWars -->
[![CodeWars](https://www.codewars.com/users/matveynis/badges/large)](https://www.codewars.com/users/matveynis)


<!-- Описание -->
## О себе

 Я программист с опытом в различных языках программирования и базах данных. Моя основная специализация включает следующие языки и технологии:

- **C++**: Я имею опыт работы с C++ и разработкой приложений на этом языке. Могу создавать эффективные и производительные решения с использованием стандартных библиотек и парадигм программирования.
- **C**: У меня также есть опыт работы с языком C, который я использую для разработки системного программного обеспечения и встроенных систем.
- **Java**: Я знаю Java и имею опыт создания масштабируемых приложений на этой платформе. Я умею работать с Java-фреймворками и инструментами разработки.
- **JavaScript**: Я владею JavaScript и использую его для разработки веб-приложений, а также для создания интерактивных пользовательских интерфейсов.
- **PHP**: У меня есть опыт работы с PHP и использования его для создания динамических веб-сайтов и веб-приложений.
- **Базы данных**: Я знаком с различными базами данных, включая PostgreSQL, MySQL, MariaDB и MongoDB. Могу проектировать, оптимизировать и управлять базами данных, а также писать эффективные запросы.

Моя цель - создавать качественное программное обеспечение и решать сложные задачи с использованием моих навыков и знаний.

<!-- Контакты -->
## Свяжись со мной

- Электронная почта: matveynis1337@mail.ru
-[Tелеграм](https://t.me/matveynis)

<!-- Футер -->
***

_На данный момент нахожусь в поисках интересных проектов._
- uses: Platane/snk@v2
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
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
