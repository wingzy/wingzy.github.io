# wingzy.github.io
Wingzy home powered by Jekyll &amp; github pages

## Quickstart
Jekyll explains itself from the code (start from /index.html), if you need help the doc is short & clear https://jekyllrb.com/docs/

### Install
To install Jekyll and all dependencies, you need a [ruby dev env](https://jekyllrb.com/docs/installation/), then:
```
gem install jekyll bundler
bundle install
```

### Run
To watch your files, build and run the website

```bundle exec jekyll serve```

To watch your SCSS & JS files, build & minify the CSS and JS

```gulp watch```

## Reminder
`_site/` is build locally or remotely (github pages) by Jekyll (there might be some Jekyll/plugins versioning issues)

`assets/css/style.css` is build from `assets/scss/style.scss` by Gulp

## Theme
Original theme https://jekyll-applin.netlify.com/

Source theme in `assets/`
