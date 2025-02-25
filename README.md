# DATA 101 Spring 2025

[![Deploy Jekyll site to Pages](https://github.com/cal-data-eng/sp25/actions/workflows/jekyll.yml/badge.svg)](https://github.com/cal-data-eng/sp25/actions/workflows/jekyll.yml) [![Run all page tests](https://github.com/cal-data-eng/sp25/actions/workflows/rspec.yml/badge.svg)](https://github.com/cal-data-eng/sp25/actions/workflows/rspec.yml)

The https://data101.org/sp25/ website.

## Installation

Prerequisites:

- You have everything that [Jekyll requires](https://jekyllrb.com/docs/installation/)
- You have installed [Bundler](https://bundler.io/): Run `gem install jekyll bundler`

1. [Fork](https://github.com/berkeley-eecs/berkeley-class-site/fork) the repository.
2. Clone your fork (replace `YOUR_GITHUB_USERNAME` and `YOUR_REPO` accordingly).
```
git clone git@github.com:YOUR_GITHUB_USERNAME/YOUR_REPO.git
```
3. Install dependencies:
```
cd sp25
bundle install
```

## Usage

To run the site locally, run:

```
bundle exec jekyll serve
```

Search throughout the repository for TODO items called `TODO(setup)` and complete them to customize the site for your course.

## Deployment

The easiest way to deploy your site is with [GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).

## Contributing

See [CONTRIBUTING.md](.github/CONTRIBUTING.md) for instructions on how to develop this site as part of course staff or if you're interested in contributing to this template repository.

## License

[BSD 3-Clause](LICENSE)
