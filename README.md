# yunc.me

Personal academic homepage of **Chen Yun (陈云)**, Tenured Associate Professor at the School of Computing and Artificial Intelligence, Shanghai University of Finance and Economics (SUFE).

Live site: <https://yunc.me>

## Local development

Requires Ruby 3.x + Bundler.

```bash
bundle install
bundle exec jekyll serve
# open http://127.0.0.1:4000
```

Or use the convenience wrapper:

```bash
./run_server.sh
```

## Editing content

All site content lives in three files:

- `_config.yml` — site identity, author block, plugin settings.
- `_data/navigation.yml` — top-bar navigation.
- `_pages/about.md` — bio, news, publications, education, service, recruiting.

Profile photo: `images/chen-yun.jpg`. Paper preview images (optional) go in `images/`.

## Deployment

Hosted on **GitHub Pages**. Push to the `main` branch and Pages builds Jekyll automatically. The `CNAME` file pins the `yunc.me` custom domain.

The Google Scholar citation crawler runs daily via GitHub Actions; it requires a repository secret named `GOOGLE_SCHOLAR_ID` (current value: `vXd0JQMAAAAJ`). On first deploy, manually trigger the workflow once to create the `google-scholar-stats` branch, then flip `google_scholar_stats_use_cdn: true` in `_config.yml`.

## Credits

Built on the [yannnnnny.github.io](https://github.com/YannnnnnY/YannnnnnY.github.io) template, which is itself a fork of [RayeRen/acad-homepage.github.io](https://github.com/RayeRen/acad-homepage.github.io). The template is in turn influenced by [mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes) and [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io). MIT licensed — see `LICENSE`.
