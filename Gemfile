source "https://rubygems.org"

gem "rails", "5.0.0.1"
gem "sprockets", ">= 4.0.0.beta2"

gemspec name: "teaspoon"

#gem for coffee-script compilations, it will solve the coffee_script not found error
group :assets do
  gem 'coffee-rails'
end


group :development, :test do
  gemspec name: "teaspoon-devkit"

  # frameworks
  gem "teaspoon-jasmine", path: "teaspoon-jasmine"
  gem "teaspoon-mocha", path: "teaspoon-mocha"
  gem "teaspoon-qunit", path: "teaspoon-qunit"

  # gems that teaspoon can utilize
  gem "selenium-webdriver"
  gem "capybara-webkit"

  # io services
  gem "codeclimate-test-reporter", group: :test, require: false
  gem "rubocop", require: false
end
