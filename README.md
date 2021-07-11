# wouzar.github.io

A personal blog.

## Build

Install Hugo:

`brew install hugo`

Run Hugo server to serve static content:

`hugo server -D`

## Deploy static site

Merge into main branch triggers action from gh-pages.yml to build Github Pages.

## Change a theme

Find a theme on https://themes.gohugo.io/tags/blog/.

Add it via submodule. For example:

`git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke`

Change theme name in config.toml:
`theme = "ananke"`