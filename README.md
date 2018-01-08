# portfolio

This Jekyll theme was originally designed for http://itzelschiaffini.github.io it contains a simple about section, a section divider, and a portfolio by categories.

You'll be able to change most settings either in `_config.yml`, `assets` or in your own `about.md`


## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "vv5-portfolio"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: vv5-portfolio
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install portfolio

## Usage

You should create an `about.md` a `_config.yml` and an `index.md` they should include:

### about.md

In your frontmatter make sure you include these tags

```yml
---
layout: page
title: About
welcome: Hi! my name is
firstname: Jane
lastname: Doe
taglines:
  - tagline1
  - tagline2
  - tagline3
---
```

and in your content include an abstract of yourself

### config.yml

```
title: Tincidunt non
catchphrase: Proin aliquam, eros eget vulputate
job: Duis suscipit varius null
jobtitle: Duis suscipit
copyright: Copyright © 2017 - Tincidunt Non. All Rights Reserved.
thanks: Proin aliquam, eros eget vulputate!
picture: /assets/brand/profile.jpg

social:
  instagram: youruser
  email: youruser@gmail.com
  tumblr: youruser
  facebook: youruser
  pinterest: youruser
```

### index.md
Finally make sure your `index.md` layout is `home`


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/vectorvcinco/jekyll-portfolio. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `portfolio.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

Profile Photo by Matheus Bertelli from Pexels https://www.pexels.com/photo/adolescence-attractive-beautiful-blur-573299/
