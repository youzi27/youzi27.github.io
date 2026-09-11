# youzi27.github.io

Personal academic homepage of **Zihui Guo** — https://youzi27.github.io

## Running Locally

Requires Ruby and Bundler ([Jekyll installation guide](https://jekyllrb.com/docs/installation/)).

```bash
bundle install
bundle exec jekyll serve
```

Then open the URL printed in the terminal (usually http://127.0.0.1:4000).

## Editing Content

Most updates only require editing data files, not HTML:

| What | Where |
| --- | --- |
| Name, bio, photo, experience, links | `_data/profile.yml` |
| Navigation bar entries | `_data/navigation.yml` |
| Homepage sections, footer text | `_data/display.yml` |
| Co-author name links | `_data/authors.yml` |
| Papers (one file per paper, grouped by year) | `_publications/<year>/` |
| News items | `_news/` |
| Blog posts | `_posts/` |
| Project / showcase entries | `_showcase/` |
| Images (photos, paper thumbnails, badges) | `assets/images/` |

Publications and news are Markdown files with YAML front matter; copy an existing
file as a starting point. Paper thumbnails go in `assets/images/publications/` and
are referenced by the `cover:` field.

## Deployment

Pushing to `main` triggers GitHub Pages' built-in Jekyll build, and the live site
updates a minute or two later.

## Credits

Built on the [academic-homepage](https://github.com/luost26/academic-homepage)
Jekyll template by [luost26](https://luost.me/), whose blog feature was contributed
by [Yuqing Xie](https://yqxie99.github.io/) and [Kun Chen](https://kwen-chen.github.io/).

## License

See [LICENSE](LICENSE).
