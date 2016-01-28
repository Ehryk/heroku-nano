heroku-nano
===========

Installs nano in a dyno and starts a bash session.

## Install

```
$ heroku plugins:install https://github.com/ehryk/heroku-nano
```

## Use

```
heroku nano
```

## Example Output
```
$ heroku nano
Running `mkdir nano
curl http://ehryk.com/Share/heroku-nano/nano.tar.gz --location --silent | tar xz -C nano
export PATH=$PATH:/app/nano
bash` attached to terminal... up, run.2135
~ $ cat README
This is your new Play application
=====================================

This file will be packaged with your application, when using `play dist`.
~ $ nano README
~ $ cat README
Changed on a dyno!
```
