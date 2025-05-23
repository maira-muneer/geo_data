# GeoData

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/geo_data`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'geo_data'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install geo_data

## Usage

To get list of all countries 
```ruby
GeoData.countries
```

To get list of cities of specific country 
```ruby
GeoData.cities("PK")
```


To get list of states of specific country 
```ruby
GeoData.states("PK")
```

To get list of cities of specific state 
```ruby
GeoData.states("PK", "Azad Kashmir")
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/geo_data. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/[USERNAME]/geo_data/blob/main/CODE_OF_CONDUCT.md).

## Code of Conduct

Everyone interacting in the GeoData project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/geo_data/blob/main/CODE_OF_CONDUCT.md).
