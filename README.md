# longrun_site

### Build CSS with
`sass scss/theme.scss docs/assets/css/theme.css`

### Watch with automatic minify
`sass --watch scss/theme.scss:docs/assets/css/theme.css --style compressed`

## Run site locally

- Install jekyll (If you have asdf then install ruby: `asdf plugin add ruby https://github.com/asdf-vm/asdf-ruby.git`,
`asdf install ruby latest`, `asdf global ruby latest`) `gem install jekyll`
- In */docs* run `bundle exec jekyll serve`
  - Use `--livereload` flag for live reloading
