Sinatra and Websockets
===

Purpose: 

* To make websockets work in a very light-weight Ruby/Sinatra app.

* To make websockets work on Parallella, too.

Based on the [eventmachine-websockets-demo](https://github.com/stewart/eventmachine-websockets-demo) repo created by the team at [Hybrid Group](http://hybridgroup.com).

Details on the thinking behind this repo are posted on the [Engine Yard Blog](https://blog.engineyard.com/2013/getting-started-with-ruby-and-websockets).

### Prerequisites

* Ruby v 1.9.3. (I tried it with Ruby 2.3.0 and it barfed all over the place. Makes sense, since this example was written a few years ago, long before Ruby 2.3.0 existed.)

* RVM. Or some other tool (like [rbenv](https://github.com/rbenv/rbenv) or [chruby](https://github.com/postmodern/chruby)) for managing Ruby versions and gemsets.

### How to Run This Demo

`$ bundle install`

`$ bundle exec ruby app.rb`

Then navigate a browser to `http://localhost:3000` and chat. Navigate a second browser to the same URL and chat between them. How cool is that!

### Sample Phrases

A few phrases for easier cut & paste during the demo...

* Greetings ConFoo from the first window!
* Salutations Confoo de la première fenêtre!
* Message sent from the second window.
* Message envoyé à partir de la seconde fenêtre.


