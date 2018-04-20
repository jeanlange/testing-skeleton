Here's one way to set up to run rspec. Look at: These files, this bash history:

```
506  mkdir testing
507  cd testing
508  mkdir lib
509  mkdir spec
510  touch lib/morse.rb
511  touch spec/morse_spec.rb
512  touch Gemfile
513  bundle
514  gem install bundler
515  sudo gem install bundler
516  bundle
517  rspec
````