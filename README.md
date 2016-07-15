# forestry-demo
A simple CMS for Jekyll and Hugo sites

## Installation

### Requirements
Installing Jekyll is easy and straight-forward, but there are a few requirements you’ll need to make sure your system has before you start.

* [Ruby](https://www.ruby-lang.org/en/downloads/) (including development headers, v1.9.3 or above for Jekyll 2 and v2 or above for Jekyll 3)
* [RubyGems](https://rubygems.org/pages/download)
* Linux, Unix, or Mac OS X
* [NodeJS](https://nodejs.org/), , or another JavaScript runtime (Jekyll 2 and earlier, for CoffeeScript support).
* [Python 2.7](https://www.python.org/downloads/) (for Jekyll 2 and earlier)

### Install with RubyGems
The best way to install Jekyll is via RubyGems. At the terminal prompt, simply run the following command to install Jekyll:
```shell
gem install jekyll
```


## Basic Usage

### DEVELOPMENT

```shell
jekyll serve
```


### BUILD

```shell
jeklyy build
```


### DEPLOY 

```shell
git subtree push --prefix _site origin gh-pages
```
