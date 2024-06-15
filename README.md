# personal-blog

Personal blog for a book reviewer, built with Jekyll and using the [alna-jekyll-theme](https://github.com/abelnnieva/alna-jekyll-theme) as the default theme.

## Getting started

### Install Ruby

```bash
# install dependencies
$ brew install chruby ruby-install xz

# install ruby
$ ruby-install ruby 2.7.8

# configure the shell
$ echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
$ echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
$ echo "chruby ruby-2.7.8" >> ~/.zshrc # run 'chruby' to see actual version
```

### Install Jekyll

```bash
# install jekyll
gem install jekyll -v 3.4.0

# install bundler
gem install bundler -v 2.4.22
```

## Build Setup

```bash
# install dependencies
bundle install

# serve with hot reload at localhost:4000
jekyll serve
```
