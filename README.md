## start-sinatra

### Simple Sinatra app


Sinatra is a [DSL](http://en.wikipedia.org/wiki/Domain-specific_language) for
quickly creating web applications in Ruby with minimal effort:

1. Create file start.rb

```
# start.rb
require 'sinatra'

get '/' do
  'Hello world from Sinatra, Nice to meet You!'
end

```

2. Install the gem:

```
$ gem install sinatra
```

3. And run with:

```shell
ruby myapp.rb
```

View at: http://localhost:4567

4. For Cloud9 IDE: Using terminal console Go to the directory where is your start.rb file and: 

```
$ ruby start.rb -p $PORT -o $IP'
```

You can see result on ...c9users.io domain.



