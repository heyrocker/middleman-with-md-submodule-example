# Middleman with Markdown Submodule Example

This is an example project using [Middleman](https://middlemanapp.com) and pulling in our [Style Guide](https://github.com/mailchimp/content-style-guide) as a submodule.

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

Initialize the submodule:
``` bash
git submodule init
```

Update the submodule:
``` bash
git submodule update
```

Run it:
``` bash
bundle exec middleman server
```

View it at `http://localhost:4567/`
