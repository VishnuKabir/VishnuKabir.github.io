# vishnukabir.github.io

Personal site of Vishnu Kabir Chhabra, built with Jekyll and deployed to the
`gh-pages` branch by GitHub Actions on every push to `master`.

## Editing content

Everything lives in a few small files:

| What | Where |
| --- | --- |
| Name, bio links, email, address | `_config.yml` (`author:`) |
| Intro paragraph | `index.html` (hero section) |
| News | `_data/news.yml` |
| Publications | `_data/publications.yml` |
| Experience, education, interests | `_data/cv.yml` |
| Styles | `assets/css/main.css` |
| Photo / CV PDF | `assets/img/portrait.jpg`, `assets/pdf/` |

## Run locally

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
