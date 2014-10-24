# Gesso

Gesso is a [Sass](http://sass-lang.com/)-based starter theme that outputs
accessible HTML5 markup. It uses a mobile-first responsive approach and
leverages [SMACSS](https://smacss.com/) for style organization. This 
encourages a component-based approach to theming through the creation of
discrete, reusable UI elements.


## Configuration 

### Configuration files

* config.rb: Ruby configuration file used for Compass compilation of Sass
files.

* Gemfile: Used by Bundler. Running `bundle install` will install the
correct versions of all required dependencies.

* Gemfile.lock: Generated by Bundler after running `bundle install`. Lists
the exact versions installed, according to the minimum requirements set in the
Gemfile.

### Sass dependencies

[Bundler](http://bundler.io) is used to manage the following dependencies and
minimum required Ruby Gem versions. (Similar to [Bower](http://bower.io/), but
for Ruby Gems.) To learn more about installing Bundler and compiling Sass, check
out README.md within the sass directory.

* [Breakpoint](http://breakpoint-sass.com): Easy to write media queries.

* [Compass](http://compass-style.org): Open-source Sass framework.

* [Sass](http://sass-lang.com): CSS on steroids. Adds nested rules, variables,
mixins, selector inheritance, and more.

* [Sass Globbing](https://github.com/chriseppstein/sass-globbing): Adds glob-
based imports to Sass.

* [Singularity](http://singularity.gs): Grid-based layout system.


 