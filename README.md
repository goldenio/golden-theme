# Golden::Theme

Provide theme helpers for Rails.

## Installation

Add this line to your application's Gemfile:

    gem 'golden-theme'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install golden-theme

## Usage

Add following to `application_controller.rb` with `:bootstrap` or `:foundation`

```
  before_action do
    golden_theme_framework :bootstrap
  end
```
