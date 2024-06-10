# Thingiverse

This is a fork of [makerbot/thingiverse-ruby](https://github.com/makerbot/thingiverse-ruby)
with the following changes:

- [Fix gemspec in order not to not require the whole gem #8](https://github.com/makerbot/thingiverse-ruby/pull/8)
- [Fix error responses exceptions and add custom exceptions #7](https://github.com/makerbot/thingiverse-ruby/pull/7)
- [Add custom exception when rate limit is exceeded #10](https://github.com/makerbot/thingiverse-ruby/pull/10)

## Installation

To use this gem, add this to your `Gemfile`:

```rb
gem "thingiverse", github: "cults/thingiverse-ruby", branch: "main"
```
