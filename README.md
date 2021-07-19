*Este projeto foi arquivado para ser substituído pelo [frontend da Plataforma de Busca do Querido Diário](https://github.com/okfn-brasil/querido-diario-frontend).*

*This project has been archived in favor of the [Querido Diário Search Platform frontend](https://github.com/okfn-brasil/querido-diario-frontend).*

---

# _Airspace_ for Jekyll
![screenshot](screenshots/home.png "Description goes here")

This Jekyll theme is a port of [ThemeFisher's](https://themefisher.com) [Airspace template](https://themefisher.com/products/airspace-free-bootstrap-website-template/). It is released under ThemeFisher's [license](https://themefisher.com/license) , which requires attribution. Concern about the licnese please contact with [them](mailto:themefisher@gmail.com)

## Usage
To start your project, [fork this respository](https://github.com/ndrewtl/airspace-jekyll/fork), put in your content, and go!


## Steps for Setup:

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
$ git clone https://github.com/okfn-brasil/querido-diario-site.git
$ cd querido-diario-site
```

Install dependencies locally:
```sh
$ bundle install --path vendor/bundle
```

This should install a local copy of jekyll.

Now run the server:
```sh
$ bundle exec jekyll serve
```
