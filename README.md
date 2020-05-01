# norioz.github.io
Personal website, served through github.pages.

## Build & Run Locally

```
bundle install
bundle exec jekyll serve
```

## How to Deploy

```
TBD
```

## Dev Info

### Ruby version (rbenv)

Install ruby with `rbenv`.

Project local ruby version is in `.ruby_version`.

### Gem and Bundler

Uses [bundler](https://bundler.io/), the ruby package manager, for tools management and installation.

### Jekyll

[Jekyll](https://jekyllrb.com/) is used for static site compiling.

#### Jekyll Basics

Pages - (HTML) unchanging pages
Posts - (MD + HTML) : Add to the `_posts` directory with a file named `YEAR-MONTH-DAY-snake-title.md`

`_site` directory is for compiled output.

Everything in `assets` is copied to the output as is.
