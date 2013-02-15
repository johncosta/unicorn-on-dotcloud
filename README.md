Sinatra + Unicorn + dotCloud
=====================================

To test locally:

- gem install bundler
- bundle install
- ruby helloworld.rb
- curl http://localhost:4567/

You should see the following:

  Hello World!


To test on dotCloud
===================

- dotcloud create -f sandbox unicorn
- dotcloud push -A unicorn

The base URL will be show at the end of the push. You can then run the same
test as shown above, by changing the URLs.