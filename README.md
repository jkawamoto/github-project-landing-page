# Github project landing page
Github landing page is a theme for [Hugo](http://gohugo.io) to create landing
pages for github projects. This theme is originally made by
[Omar Abdelhafith](https://github.com/oarrabi), and licensed under the MIT
license. See [LICENSE](LICENSE.md) for more information.


## Demo
A demo site is provided by [Swiftline](http://swiftline.github.io).


## Screenshot
![screenshot](https://raw.githubusercontent.com/jkawamoto/github-project-landing-page/master/images/screenshot.png)


## Costumization
Check [config.toml](https://github.com/jkawamoto/github-project-landing-page/blob/master/exampleSite/config.toml) for available configuration.
Below is a description for each of them.

Project sub title appears after project name
```toml
[params]
  SubTitle = "Amazing project."
```

- `AuthorURL` a link of the project author.
- `GithubURL` link to project url

```toml
[params]
  AuthorURL = "https://www.jkawamoto.info/"
  GithubURL = "https://github.com/jkawamoto/gii"
```

- `GithubRepo` github author account name
- `GithubRepo` github project name

```toml
[params]
  GithubRepo = "github-project-landing-page"
  GithubOrg = "jkawamoto"
```

Theme colors
```toml
[params]
  first_color="#f8f8f8"
  first_border_color="#e7e7e7"
  first_text_color="#333"

  second_color="white"
  second_text_color="#333"

  header_color="#f8f8f8"
  header_text_color="rgb(51, 51, 51)"

  header_link_color="#777"
  header_link_hover_color="rgb(51, 51, 51)"
```

## License
This software is released under the MIT License, see [LICENSE](LICENSE.md).
