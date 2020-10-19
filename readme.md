# Middleman with Style Guide Example

This is an example project using [Middleman](https://middlemanapp.com). 

## Installation
Requires Ruby 2.2.5 and Bundler

Clone the repo:
``` bash
git clone git@github.com:mailchimp/middleman-with-md-submodule-example.git
cd middleman-with-md-submodule-example
```

Install dependencies:
``` bash
bundle install
```

Run it:
``` bash
bundle exec middleman server
```

View it at `http://localhost:4567/`

## Development
Site content is held in Markdown files which can be found in /content-style-guide.

Visual styling is done with Sass, which can be found in /source/stylesheets/site.css.scss. 

Templates are found in /source/layouts. Articles can control which layout they use by adjusting the metadata found at the top of each article.


## Build
Ater doing CSS changes or when preparing to deploy:

``` bash
bundle exec middleman build
```

Built site can be found in /build