# jacobtx.github.io

Source for my personal academic portfolio → **<https://jacobtx.github.io>**

I'm **Jacob Thomas Sony**, a Dual Degree (B.Tech + M.Tech) student in Mechanical
Engineering at IIT Bombay. The site collects my research, projects, publications,
and CV.

## Built with

- [Jekyll](https://jekyllrb.com/) + the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)
  theme (MIT) — see [Credits](#credits).
- A custom **"sigma"** skin (black + bright-red/`#F53B22` palette, sampled from my
  emblem) with a **light/dark theme switch** that follows the OS on first visit.
- **Michroma** for the masthead title, **Nunito** for body and headings,
  **IBM Plex Mono** for code.
- Content organised into `research`, `projects`, and `publications` collections,
  plus an About page and a CV page with a downloadable PDF.

## Running locally

Requires Ruby (3.0+) and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Structure

| Path | What it holds |
| --- | --- |
| `index.md` | About / home page |
| `_pages/` | Research, Projects, Publications, and CV pages |
| `_research/`, `_projects/`, `_publications/` | Collection entries |
| `_sass/_jts-*.scss`, `_sass/minimal-mistakes/skins/_sigma*.scss` | Custom fonts, overrides, and skins |
| `_includes/head/custom.html`, `_includes/footer/custom.html` | Web fonts, favicon, and the theme-switch script |
| `assets/` | Images, the emblem logo/favicon, and the CV PDF |

## Credits

Built on the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)
Jekyll theme by [Michael Rose](https://mademistakes.com), used under the MIT
License. See [`LICENSE`](LICENSE) for the full theme license and third-party
attributions.
