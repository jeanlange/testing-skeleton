Here's one way to set up to run RSpec with a basic Ruby project.

Look at:
* These files
* This (cleaned-up) bash history (I promise I didn't get it totally all the way right the first time, either):

```
506  mkdir testing
507  cd testing
508  mkdir lib
509  mkdir spec
510  touch lib/morse.rb
511  touch spec/morse_spec.rb
512  touch Gemfile
513  sudo gem install bundler
514  bundle
515  rspec
````
