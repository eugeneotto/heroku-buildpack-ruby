# Heroku Buildpack for Ruby with Sqlite3

This is a [Heroku Buildpack](http://devcenter.heroku.com/articles/buildpacks) for Ruby, Rack, and Rails apps. It uses [Bundler](https://bundler.io) for dependency management.

This buildpack requires 64-bit Linux.

It adds sqlite3 support by borrowing from this fork of heroku-buildpack-ruby: https://github.com/yotsumoto/heroku-buildpack-ruby-with-sqlite3

## Usage

```sh
heroku buildpacks:set https://github.com/yotsumoto/heroku-buildpack-ruby-with-sqlite3
git push heroku master
```

