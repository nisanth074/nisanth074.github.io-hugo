# nisanth074.github.io-hugo

This repository contains the source code of my [blog](https://nisanth074.github.io)

## Installation & Usage

The blog is built with [Hugo](https://gohugo.io/), a fast static site generator written in the Go programming language

First, install hugo
```
brew update && brew install hugo
```

Clone the repository
```
cd ~/Projects/
git clone git@github.com:nisanth074/nisanth074.github.io-hugo.git
```

To view the blog in your browser, run
```
hugo server --buildDrafts --watch
```
and visit http://localhost:1313/

To publish the blog after adding a blog post, run
```
bin/deploy
```

## Why

Why build a custom blog?

Its mostly an experiment to learn CSS.
