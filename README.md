# Portfolio - Matthew G. Yang

  ![Logo](https://dl.dropboxusercontent.com/u/69636/2015-08-18%2011.53.43-1.jpg)

By [Matthew Yang](http://www.matthewgyang.com).

## Description
**Portfolio** This is a portfolio Rails application

## Specifications

App was created without the default test suite with this command:

```console
rails new portfolio --skip-test-unit
```

Then the following gems were added to the gem file:

```ruby
gem "minitest-rails"
```

```console
rails generate minitest:install
```

```ruby
group :test do
  gem "minitest-rails-capybara"
end
```

Then the following was added to `test/test_helper.rb`

```ruby
require "minitest/rails/capybara"
```

## Credit
This gem instructions were taken directly from the following github repos:

[minitest-rails](https://github.com/blowmage/minitest-rails)

[minitest-rails-capybara](https://github.com/blowmage/minitest-rails-capybara)
