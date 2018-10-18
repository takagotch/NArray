### NArray
---
https://github.com/ruby-numo/numo-narray


```
gem install -y git ruby gcc ruby-dev rake make
gem install specific_install
gem specific_install https://github.com/ruby-numo/numo-narray.git

# pry >
require "numo/narray"
a = Numo::DFloat.new(3,5).seq
a.shape
a.ndim
a.class
a.size

ruby setup.rb
bundle install
bundle exec rake test
bundle exec ruby test/bit_test.rb --location 27

```

```ruby

```

```

```


