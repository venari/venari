Venari website hosted at [venari.co.nz](venari.co.nz).

```
bundle exec jekyll serve --livereload --host=0.0.0.0
```

- or to include draft posts:
```
bundle exec jekyll serve --livereload --drafts --host=0.0.0.0
```
Cloned from [this respository](https://github.com/ndrewtl/airspace-jekyll/fork), which is a Jekyll theme is a port of ThemeFisher's Airspace template. It is released under ThemeFisher's f

# Steps for Setup:

### Make sure you have Ruby

First, make sure you have [Ruby](https://www.ruby-lang.org/en/) installed. You can confirm this by running `ruby -v` on the command line:

```sh
$ ruby -v
ruby [version number] (date) [your platform]
```

If you get something like `"Error, command not found"` visit the link above and
install Ruby for your platform.


### Make sure you have Bundler

Next, make sure you have [Bundler](https://bundler.io) installed. Just like
above, run `bundle -v` on the command line:

```sh
$ bundle -v
bundle [version number]
```

If you get `"Error, command not found"` run `gem install bundler` to install it
using RubyGems.

### Run this repository

Clone the repository, and `cd` into it:
```sh
$ git clone https://github.com/venari/venari.git
$ cd venari
```

Install dependencies locally:
```sh
$ bundle install --path vendor/bundle
```

This should install a local copy of jekyll.

Now run the server:
```sh
$ ./vendor/bundle/ruby/#{YOUR_RUBY_VERSION}/bin/jekyll server
```



## TO DO

- [ ] Add comments functionality:
  - https://haacked.com/archive/2018/06/24/comments-for-jekyll-blogs/
  - https://staticman.net/
  - https://www.talkyard.io/blog-comments
