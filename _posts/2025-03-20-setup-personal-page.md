---
title: 'Setup Personal Page'
date: 2013-08-14
permalink: /posts/2025/03/setup-personal-page/
tags:
  - setup tutorial
---

Using WSL:

``` shell
sudo apt install ruby-dev ruby-bundler nodejs
sudo apt update
sudo apt install -y build-essential ruby-dev zlib1g-dev libffi-dev libyaml-dev libgdbm-dev libncurses5-dev libreadline-dev libssl-dev
```
then

``` shell
bundle install
```

To run blog locally

``` shell
bundle exec jekyll serve -l -H localhost
```