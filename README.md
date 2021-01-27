# opensourceeconomics.github.io

This is the source code for the OSE website. Edit the respective `*.md` files directly.

## Instructions for Building Locally

This website uses Jekyll.

For official guides to install Jekyll, see [Installation | Jekyll • Simple, blog-aware, static sites](https://jekyllrb.com/docs/installation/).

For GitHub's guide to locally build and test the website, see [Testing your GitHub Pages site locally with Jekyll - GitHub Docs](https://docs.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll).

The basic steps are:

1. Clone this repository to local machine.
1. Run `jekyll --version` to make sure you have jekyll installed correctly.
1. Run `bundle install` to make sure you have all the dependencies installed.
    - Alternatively, if file `Gemfile.lock` already exists, run `bundle update`.
1. Run `bundle exec jekyll serve --livereload` to start local server.
    - Note: you should access the `Server address` instead of `LiveReload address`. 
