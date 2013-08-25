Gutenberg
=========

[**Documentation**](http://rubydoc.info/github/somu/gutenberg/master/frames)  
[**Gem**](http://rubygems.org/gems/gutenberg)

**Gutenberg** is a README.md lifesaver when you are writing it large.

It uses [semantic versioning](http://semver.org) and [Mustache](http://mustache.github.io), both
are cool and I appreciate their usage.

It generates static readme file from Mustache-powered markdown files,
which link automatically. It has a built-in library of mixins, which
you can port into your view.rb via including `Gutenberg::Mixins` module.
More on that later, now basic features and how get it working.

It has a built-in task for Rake, so you include it in your Rakefile:

```ruby
require 'gutenberg/task'
Gutenberg::Task.new
```
