# DReaMS website

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fdreams-community.github.io&style=flat-square)](https://dreams-community.github.io)

This is the source repository for the **DReaMS website**, built with [Jekyll](https://jekyllrb.com/) using the [Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/). This site is deployed via GitHub Pages and contains information about the DReaMS network, its members, and activities.

---

## Development

You need Ruby (>= 3.3 recommended) and Bundler installed:
```bash
gem install bundler
bundle install
```

Run a local server with:
```bash
bundle exec jekyll serve
```
The site will be available at http://localhost:4000.

## Deployment

This site uses CI for automatic deployment to GitHub Pages. 
Deployment runs on pushes to the main branch.

## Known Limitations

Some Sass code (from upstream theme) emits deprecation warnings due to changes in Sass v2/v3. 
This does not affect build correctness but may require theme update in the future.

---

## License
This project is licensed under the Apache 2.0. See the [LICENSE](LICENSE.txt) file for details.

