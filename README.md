Heroku buildpack: CJK font
=======================

This is a [Heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) for CJK font support.

Usage
-----

Example usage:

```shell
$ heroku create --buildpack https://github.com/evosystem-jp/heroku-buildpack-cjk-font

# or if your app is already created:
$ heroku buildpacks:add https://github.com/evosystem-jp/heroku-buildpack-cjk-font

$ git push heroku master
```