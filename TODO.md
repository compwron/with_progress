update gems
  spec.add_dependency 'ruby-progressbar', '~> 1.4'
  spec.add_development_dependency 'backports', '~> 3.5'

  spec.add_development_dependency "bundler", "~> 1.3"
  
update spec to not use should

Deprecation Warnings:

Using `should` from rspec-expectations' old `:should` syntax without explicitly enabling the syntax is deprecated. Use the new `:expect` syntax or explicitly enable `:should` with `config.expect_with(:rspec) { |c| c.syntax = :should }` instead. Called from /Users/lindag/Development/with_progress/spec/with_progress_spec.rb:16:in `block (3 levels) in <top (required)>'.


If you need more of the backtrace for any of these deprecations to
identify where to make the necessary changes, you can configure
`config.raise_errors_for_deprecations!`, and it will turn the
deprecation warnings into errors, giving you the full backtrace.

1 deprecation warning total

Autoformat 

use '' instead of ""

bump version and changelog

add new rubies to CI build

PR!

