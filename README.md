# PortfolioBlog Application

> A Ruby on Rails 5.2 application for a hybrid Portfolio / Blog website

### Features

- Real time chat engine for comments
- Blog
- Portfolio
- Drag and drop interface

### Configuration

* Ruby version => 2.5

* Rails version => 5.2

* System dependencies

* Configuration

* Database creation

* Database initialization

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Travis CI

### Automated Continuous Integration with Travis CI

Continuous Integration (CI) is the practice of integrating new code into the master branch frequently, to help detect merge conflicts, bugs, and improve the quality of the software a development team writes.

CI is usually accompanied by running an application's test suite against the latest code changes, and flagging any test failures that are found. Developers are expected to investigate and fix these failures to maintain a passing test suite and therefore quality.

[Travis CI](https://travis-ci.org) is a build server that helps automate the CI process. Travis CI runs an application's tests against the latest changes pushed to the application's code respository. In this project, Travis CI runs the project's tests (`rake test`) on pull requests and on changes to the master branch.

Travis CI configuration how-to and example:
- [.travis.yml](.travis.yml) - Travis CI's configuration file (with instructions)
- [DelishDish Travis CI build!](https://travis-ci.org/bennypaulino/portfolio_blog)
- Travis CI badge for DelishDish: [![Build Status](https://travis-ci.org/bennypaulino/delish-dish.svg?branch=master)](https://travis-ci.org/bennypaulino/portfolio_blog)
