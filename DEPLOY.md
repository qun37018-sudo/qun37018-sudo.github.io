# Deployment

Target repository:

```text
qun37018-sudo/qun37018-sudo.github.io
```

Recommended steps:

```bash
git init
git add .
git commit -m "Build Qun Chen academic homepage"
git branch -M main
git remote add origin git@github.com:qun37018-sudo/qun37018-sudo.github.io.git
git push -u origin main
```

In GitHub, enable Pages from the `main` branch. The site is a standard Jekyll/GitHub Pages repository with content in `_pages`, `_publications`, `cv.html`, and `_config.yml`.

For local preview:

```bash
bundle install
bundle exec jekyll serve
```
