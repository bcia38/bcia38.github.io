# BCIA Public Website

[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Usage

### How to install (on Windows)

1. Install [Ruby](https://rubyinstaller.org/downloads/) version 2.4.0 or above (`ruby -v`)
2. Run the `ridk install`
3. Install gems depencies: `bundle install`

### How to install (on Mac)

1. gem install bundler
2. Run the `ridk install`
3. Install gems depencies: `bundle install`

### How to run locally

1. On the first run, you need to install dependencies
```shell
bundle install
```

2. Then run the local server
```shell
bundle exec jekyll serve --trace --drafts
```

3. Browse to the page http://127.0.0.1:4000

### How to update Ruby dependencies

```shell
bundle update
```
