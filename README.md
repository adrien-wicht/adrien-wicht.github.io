# Adrien Wicht — Academic Website

This repository contains the source code for Adrien Wicht’s academic website, powered by [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme.

## 🐳 Docker Quickstart

You can build and serve the site using Docker (no need for Ruby or Jekyll on your host machine):

```bash
docker run --rm \
  -p 4000:4000 \
  -v "$PWD":/srv/jekyll \
  jekyll/jekyll:4 \
  jekyll serve --livereload --future
