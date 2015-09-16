rails\_spawn: Spawn a new Rails application from this.
======================================================

Global pre-requisite
--------------------

- Install rbenv.

    $ git clone https://github.com/sstephenson/rbenv.git ~/.rbenv

- Install ruby-build in rbenv.

    $ git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build

- Install rbenv-binstubs in rbenv.

    $ git clone https://github.com/ianheggie/rbenv-binstubs.git ~/.rbenv/plugins/rbenv-binstubs

- Install rbenv-gem-rehash in rbenv.

    $ git clone https://github.com/sstephenson/rbenv-gem-rehash.git ~/.rbenv/plugins/rbenv-gem-rehash

- Install a Ruby version.

    $ rbenv install 2.2.3

- Check the Ruby version.

    $ mkdir tmp
    $ cd tmp/
    $ rbenv local 2.2.3

    $ rbenv version
    $ rbenv versions
    $ rbenv which ruby
    $ rbenv which gem

- Install Bundler.

    $ rbenv gem install bundler

- Check Bundler.

    $ rbenv exec gem which bundler
    $ gem which bundler

Local log
---------

- Specify Ruby's version.

    $ rbenv local 2.2.3
