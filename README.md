# onefatgiraffe.com
[![GitHub license](https://img.shields.io/github/license/FriendsOfCake/FriendsOfCake.github.io.svg?style=flat-square)](https://github.com/onefatgiraffe/onefatgiraffe.github.io/blob/master/LICENSE)
[![Twitter](https://img.shields.io/badge/contact-@onefatgiraffe-blue.svg?style=flat-square)](https://twitter.com/onefatgiraffe)

Official company website.

## License

You may feel free to re-use any part of the structure, design, and layout of this site;
It is under MIT license. However, logo icons and page content are copyright One Fat Giraffe Inc. You may not reuse them. 

## Development Notes

### Setting up a local instance

This project is setup to use [Bundler](http://bundler.io/), [Jekyll](http://jekyllrb.com/), and [Bower](http://bower.io/).

After cloning this repository, run:

1. `bundle install` to download dependencies required to build.
2. `bower install` to download front-end packages into the `./components` directory. (This is not necessary for the `master` branch.)
3. `bundle exec jekyll serve` to run locally or `jekyll build` to generate into `./site` directory.