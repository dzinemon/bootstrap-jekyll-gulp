# Template

(PREVIEW)[https://dzinemon.github.io/bootstrap-jekyll-gulp/]

- Stack: Jekyll + Gulp 4 + Bootstrap 4 + Browser-sync

## Install site and site dependencies

1. Clone or download this repository.
1. Run `npm install` (*this step is optional if you update content only: images/text/data files*)
1. Run `bundle install` (*required for Jekyll*)

## Running

* **For Development** Run `gulp` to bundle assets (js/styles) and generate website into *_site* folder
* **For Editing** should be using `bundle exec jekyll serve` to run server or *Option with force livereload browser `bundle exec jekyll serve --livereload`*

*Dev Note:* Check gulpfile.js for automated tasks, like `gulp purgecss` to update critical css
