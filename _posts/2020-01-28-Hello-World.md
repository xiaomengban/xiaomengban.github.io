---
layout: post
title: Test Jekyll with GitHub Pages locally on Ubuntu
---

## Environment Setup

First, install Ruby and related dependencies:
```
sudo apt-get install ruby-full build-essential zlib1g-dev
```

Then, install Jekyll and the plug-ins used by GitHub Pages:
```
gem install github-pages
```

> If installation of github-pages failed due to Ruby version, try using the brightbox ruby-ng ppa.
> sudo apt-add-repository ppa:brightbox/ruby-ng
> sudo apt update
> sudo apt install ruby2.6 ruby2.6-dev