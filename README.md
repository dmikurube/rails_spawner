rails\_spawn
============

Spawn a new Rails application from this.

Global pre-requisite
--------------------

- Install rbenv.

```
$ git clone https://github.com/sstephenson/rbenv.git ~/.rbenv
```

- Install ruby-build in rbenv.

```
$ git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
```

- Install rbenv-binstubs in rbenv.

```
$ git clone https://github.com/ianheggie/rbenv-binstubs.git ~/.rbenv/plugins/rbenv-binstubs
```

- Install rbenv-gem-rehash in rbenv.

```
$ git clone https://github.com/sstephenson/rbenv-gem-rehash.git ~/.rbenv/plugins/rbenv-gem-rehash
```

- Install a Ruby version.

```
$ rbenv install 2.2.3
```

- Check the Ruby version.

```
$ mkdir tmp
$ cd tmp/
$ rbenv local 2.2.3

$ rbenv version
$ rbenv versions
$ rbenv which ruby
$ rbenv which gem
```

- Install Bundler.

```
$ rbenv gem install bundler
```

- Check Bundler.

```
$ rbenv exec gem which bundler
$ gem which bundler
```

Usage
-----

- Clone the repository.

```
$ git clone https://github.com/dmikurube/rails_spawner.git
```

- Install Rails and its dependencies.

```
$ bundle install --path vendor/bundle --binstubs vendor/bin
```

- Check rbenv.

```
$ which rails
$ rbenv which rails
```

- Spawn a new Rails application!

```
$ rails new ../your-new-application --skip-bundle
```

After spawn
-----------

- Go to the new Rails application directory.

```
$ cd ../your-new-application
```

- Make it a Git repository.

```
$ git init
```

- Specify Ruby's version.

```
$ rbenv local 2.2.3
```

- Download .gitignore from GitHub.

```
$ curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/master/Rails.gitignore
```

- Add vendor/bin/ to be ignored in .gitignore.

```
$ vi .gitignore
```

- Check Gemfile.

```
$ cat Gemfile
```

- Install Rails and its dependencies.

```
$ bundle install --path vendor/bundle --binstubs vendor/bin
```

- Check rbenv.

```
$ which rails
$ rbenv which rails
```

- Start the Rails server.

```
$ rails s
```

Local log
---------

- Specify Ruby's version.

```
$ rbenv local 2.2.3
```

- Generate Gemfile.

```
$ bundle init
```

- Update Gemfile for a specific Rails version. (Uncomment "rails" and add a version "4.2.4".)

```
$ vi Gemfile
```

- Download .gitignore from GitHub.

```
$ curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/master/Rails.gitignore
```

- Add vendor/bin/ to be ignored in .gitignore.

```
$ vi .gitignore
```

- Install Rails and its dependencies.

```
$ bundle install --path vendor/bundle --binstubs vendor/bin
```
